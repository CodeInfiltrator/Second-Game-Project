# Second-Game-Project

## TicTacToe Game

The Tic Tac Toe game described in the document is a digital implementation of the classic game where two players take turns marking spaces in a 3x3 grid, aiming to align three of their symbols (X or O) either horizontally, vertically, or diagonally. The game supports two modes: playing against another player locally or against a bot.

### Key Features:

1. **Display Board**: A function to print or display the current state of the Tic Tac Toe board.
2. **Check Win**: A function to determine if there is a winner by checking for three matching symbols in a row, column, or diagonal.
3. **Check Board Full**: A function to check if the board is full, indicating a draw.
4. **Score File**: A function to process and save the game history and scores.
5. **Best Move**: A function used by the bot to determine the best move, aiming to either win the game or block the opponent's winning move.
6. **Tic Tac Toe**: The main function to initialize the board, handle player moves, check for a win or draw, update scores, and manage the game mode (player vs player or player vs bot).
7. **Menu**: A function to display the game menu and manage user choices to play the game, view scores, or exit.
8. **Main**: The primary function that initiates the game and controls the overall flow.

### Additional Details:

- **Linked List Representation**: The game board is represented using a linked list, with each node representing a cell on the board. For a 3x3 board, the linked list consists of 9 nodes.
- **Game Modes**:
  - **Single Player (Bot)**: The player competes against a simple bot that chooses moves randomly from available cells.
  - **Multiplayer**: Two players play locally on the same computer, taking turns.
  - **File Saving**: The game includes functionality to save the score history of each session, allowing users to view past results.

_© The game was developed by Mikhael Henokh Santoso, Michael Wijaya, and Emmanuelle Frizzia Darren._
