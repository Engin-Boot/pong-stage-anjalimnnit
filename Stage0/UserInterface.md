# User Interface

## Feature

This module with take care of the user interface of the game which
includes background setup, setup screen size, balls
and paddles for both the players.
Ball is placed in the center of the screen and paddles at the two ends.
Initial score of the players 0 is displayed on the screen.

## Acceptance Criteria

### Scenario: Setting up the game

Given: The user has entered the game.

When : The user clicks on the setting button.
And the default settings are available.

Then: User can choose the background from the available options.
User can set the size and color of ball and the paddles.

### Scenario: User clicks on the start button

Given: The user has already customized the settings.

When: The user clicks on the start button.

Then: User can see the ball placed in the center of the screen.
Paddles at the two corners of the screen.
Score of both players displayed as 0 on the screen.
