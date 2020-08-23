# Interaction Sequences

## Startup Sequence

```mermaid
sequenceDiagram
GameController->>+Ball: On click of start button start moving the ball
 Ball->>+GameController: After clicking start button Ball starts moving in random directions

```

## Movement Initiation

```mermaid
sequenceDiagram
GameController->>+Paddle: Game has started then players can start moving their paddles
GameController->>+Ball: As the game starts ball starts moving automatically. 
Ball->>+GameController: As the ball hits the back of paddle restart the game.
```

## One score

```mermaid
sequenceDiagram
Ball->>+GameController: As the ball hits the back wall of any one of the padddle,increase the score of the respective player
GameController->>+Ball: Increased the score of player.Start moving the ball again.

```
