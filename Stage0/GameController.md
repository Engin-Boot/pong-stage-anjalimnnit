# GameController

## Feature

This feature takes care of the collisions between the balls.

## Acceptance Criteria

### Scenario: Starting the game

 Given - The user interface is set up.

 When - The user 

 Then - We can see two paddles and a ball
        and intial scores of players are set to 0
        and the game starts by clicking on the ball.

### Scenario: Incrementing the score of the player

 Given - The initial scores of player 1 and player 2

 When - The ball touches the back of paddle of one of the player

 Then - IncrementScore() of another player and update the score on the screen.
        For player 1 score1++
        For player 2 score2++

### Scenario: Any player press exit

 Given: The game is functioning properly.

 When : Any one of the player presses exit.

 Then: Show option as Quit game or Restart game.
       Quit game exits and delete the space for ball and paddle
       Restart game starts the game from the beginning.

### Scenario: One of the player wins

 Given: The game is functioning properly

 When : The score of any one of the player == 15

 Then : Stop the game and show a message "Player 1 or 2 wins"

### Scenario: Playing sound when the ball hits the padddle

 Given: The game is functioning properly.

 When: The ball hits the paddles

 Then: Play a sound.
