# Ball

## Feature

This module is for managing the ball for the pong game.
Here we can Reinitialize() the ball.
And MoveBall() moves the ball in random direction.

## Acceptance Criteria

### Scenario: Moving the ball when the game starts

  Given - The players have joined.

  When - Player clicks on the ball.

  Then - The ball starts moving in random direction using MoveBall().

### Scenario: Reinitializing the ball when the player scores a point

 Given - The game is going on

 When - The player scores a point.

 Then - Reinitialize the ball
 And place it in the center of the screen

### Scenario: Ball changes direction when hits anything

 Given - The game is functioning properly
         and the ball is moving randomly.

 When - The ball hits the wall or the paddles

 Then - The ball reflects back in other direction.

### Scenario: Increasing the ball speed

 Given - The game is functioning properly
         and the ball is moving randomly.
 When - The score of any of the player == 5
 Then - Increase the speed of the ball.
