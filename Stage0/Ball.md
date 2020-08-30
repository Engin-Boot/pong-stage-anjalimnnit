# Ball

## Feature

This module is for managing the ball for the pong game.
Here we can Reinitialize() the ball.
And  move the ball in random direction.

## Acceptance Criteria

### Scenario: Starting the game

  Given - The UI is setup .

  When - Player clicks on the ball.

  Then - The ball starts moving in random directions.

### Scenario: The ball hits the back wall of paddle

 Given - The game is going on.

 When - The ball hits the back of paddle.

 Then - Reinitialize the ball
 And place it in the center of the screen.
 And tell the Game Controller to update the scores.

### Scenario: Ball changes direction when hits anything

 Given - The game is functioning properly
         and the ball is moving randomly.

 When - The ball hits the wall or the paddles

 Then - The ball reflects back in other direction.
