# Tic-Tac-Toe Game Implementation (JavaFX)

## This program implements a two-player Tic-Tac-Toe game using JavaFX for the GUI. It includes a 3x3 grid where players alternate turns to place "X" and "O" markers on the grid.

## Key Features:
- Grid Layout: The board consists of a 3x3 grid, implemented using JavaFX's GridPane. Each cell is a Button, which responds to player clicks.

- Turn Logic: The game alternates between "X" and "O" on each turn. The current player's move is marked in the clicked cell.

- Winning Condition: The game checks for a winner after each move by examining all possible winning lines (rows, columns, diagonals). If a player wins, an alert box is shown.

- Draw Condition: If the board is full and no player has won, a draw is declared.

- Reset: After each game (win or draw), the board is reset for a new game.

# How It Works:
The game starts with an empty grid where each cell is a Button.

When a player clicks a button, the corresponding cell is marked with either "X" or "O" based on the current player’s turn.

After each move, the game checks for a winner by checking rows, columns, and diagonals for matching symbols.

If a winner is found or the board is full, a message box pops up, informing the players of the result.

The game automatically resets after each game round.

