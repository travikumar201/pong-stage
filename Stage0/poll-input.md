# Poll Input

## Feature

This module helps user select either a single player or double player game

## Acceptance Criteria

The game operates for single as well as double player mode

### Scenario: Selecting single player mode

  Given that the game has no bugs and allows single player option

  When I select single player mode

  Then computer becomes the second player

### Scenario: Selecting double player mode

  Given that the game has no bugs and allows double player game

  When I select double player mode

  Then two players can play the game simultaneously
