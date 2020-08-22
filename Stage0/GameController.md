# GameController

## Feature

This module with take care of the user interface of the game i.e.
setup the background, setup screen size, balls
and paddles for both the players.
Ball is placed in the center of the screen and paddles at the two ends.
Initial score of the players i.e. 0 is displayed on the screen.
The score of the players is increased using IncrementScore().

## Acceptance Criteria

### Scenario: Incrementing the score of the player

 Given - The initial scores of player 1 and player 2

 When - The ball touches the back of paddle of one of the player

 Then - IncrementScore() of another player and update the score on the screen.

### Scenario: any player press exit
 Given: The game is functioning properly.

 When : Any one of the player presses exit.

 Then: Quit() game and delete the space for ball and paddle.
       OR Restart the game using Restart()

  
              