# Count Points

## Feature

This module will count individual points and declare
the winner when any one of the player receives 10 points first.

## Acceptance Criteria

Finish the game or restart a new game when any one
player wins a game

### Scenario: Count individual points

  Given that the game is bug free

  When I miss to touch the pong ball using my pad

  Then the other player gets one point and vice versa

### Declare the winner

  Given that the game is bug free

  When any one of the two players reaches 10 points first

  Then that player is declared the winner
  