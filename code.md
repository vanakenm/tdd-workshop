
# Practical example

Create a small example, TDD way

- Calculator
  - from string
  - we're not testing the user interaction (let's put it in another class!) - "separation of concerns"
  - "3 + 4"
  - "3 + 4 + 5"
  - "3 x 4"
  - "3"
  - "4 / 2"
  - "4 / 0"
  - "2 + A"
  - "3 + 4 * 5"
  - "(3 + 4) * 5" (resolve parenthesis first)
  - "" (resolve inner parenthesis first)

- TicTacToe

2 player (no AI)

  - Game is empty
  - First players play
  - Game is not finished
  - Play: board is not more empty
  - Play: piece is visible
  - Play: not outside the board
  - Play: not if not empty
  - Play: not the proper player turn (update to not ask the player)
