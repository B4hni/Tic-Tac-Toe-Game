# Tic Tac Toe Game
This is a simple Tic Tac Toe game built using Python's Pygame library. The game is designed for two players, who alternate turns to place their mark (X or O) on a 3x3 grid. The objective is to get three of their marks in a row, column, or diagonal before their opponent does.

## Features
- **Winning Detection**: The game detects when a player has won and displays the winning line.
- **Draw Detection**: If all cells are filled and no player has won, the game declares a draw.
- **Graphical Interface**: A user-friendly interface with images representing X and O.
- **Automatic Reset**: After a game ends (win or draw), the game automatically resets after a short pause.

## Game Rules
1. The game is played on a 3x3 grid.
2. Player take turns to place their mark (X or O) in an empty cell.
3. The first player to get three of their marks in a row (vertically, horizontally, or diagonally) wins the game.
4. If all cells are filled and no player has won, the game ends in a draw.
5. After a game concludes, the board resets for a new game.

You can install the Pygame library using pip:
```bash
pip install pygame
