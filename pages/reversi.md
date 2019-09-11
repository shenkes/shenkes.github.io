## About Reversi

[Download](/projects/Reversi.zip)

**Project description:** (Finished - May 2019) <br>
As one of 4 games I made in the Game Development course (COMS 437), I created a single player version of Reversi in Unity using C#. The computer player uses the [Minimax Algorithm](https://www.geeksforgeeks.org/minimax-algorithm-in-game-theory-set-1-introduction/) to determine its next move. There are 5 difficulties to the game and each difficulty can see 1-5 turns ahead of the current game state in correlation to the difficulty. I completed the Reversi game in a couple days and challenged my friends to beat the AI I created. I learned the Minimax Algorithm in making this game, but more importantly I was able to envision many different ways the AI could be modified to learn or suit other games. As a quick example: the AI could store the number of wins and losses for each move that had been tried and use that information in the heuristic to make up for the fact that it can only see 5 turns in the future.

### Game in Action

<img src="/images/reversi.png?raw=true" width="500"/>

### Next Steps
I achieved my original goals in making the Particle System, but if I came back to it I have a few things I would like to do.
* Embed the game in this page
* Implement [alpha-beta pruning](https://en.wikipedia.org/wiki/Alpha%E2%80%93beta_pruning)
* Add a menu
* Add an end game animation
* Allow local multiplayer
* Add sounds
* Choose/alternate between white and black
* Improve UI
