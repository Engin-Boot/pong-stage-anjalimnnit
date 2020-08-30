# Game Controller

## Feature

This feature takes care of the collisions between the balls.

## Acceptance Criteria

### Scenario: Incrementing the score of the player

 Given - The initial scores of player 1 and player 2

 When - The ball touches the back of paddle of one of the player

 Then - Increment Score of another player and
 tell UI to update the score on the screen.
        For player 1 score 1 ++
        For player 2 score 2 ++

### Scenario: Any player press exit

 Given: The game is functioning properly.

 When : Any one of the player presses exit.

 Then: Show option as Quit game or Restart game.
       Quit game exit the game.
       Restart game starts the game from the beginning.

### Scenario: One of the player wins

 Given: The game is functioning properly

 When : The score of any one of the player == 15

 Then : Stop the game and UI show a message "Player 1 or 2 wins"

### Scenario: Playing sound when the ball hits the paddle

 Given: The game is functioning properly.

 When: The ball hits the paddles

 Then: Play a sound.
