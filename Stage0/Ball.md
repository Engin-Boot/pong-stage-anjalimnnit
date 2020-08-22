# Ball

## Feature

This module is for managing the ball for the pong game.
Here we can Reinitialize() the ball
And MoveBall() moves the ball in random directions.

## Acceptance Criteria

### Scenario: Moving the ball when the game starts

  Given - The players have joined

  When - We start the game.

  Then - The ball starts moving in random direction using MoveBall().

### Scenario: Reinitializing the ball when the player scores a point

 Given - The game is going on

 When - The player scores a point.

 Then - Reinitialize() the ball
 And place it in the center of the screen
 