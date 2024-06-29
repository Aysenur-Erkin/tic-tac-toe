Tic tac toe in Python
# Tic Tac Toe Game

This is a simple Tic Tac Toe (XOX) game implemented in Python. Two players take turns to place their mark (X or O) on the 3x3 grid. The player who succeeds in placing three of their marks in a horizontal, vertical, or diagonal row wins the game.

## Features

- Two-player mode.
- Simple text-based interface.
- Detects win, loss, and draw conditions.

## Prerequisites

- Python 3.x installed on your machine.

## Getting Started

1. **Clone the repository**

    ```sh
    git clone https://github.com/Aysenur-Erkin/tic-tac-toe.git
    cd tic-tac-toe
    ```

2. **Run the game**

    ```sh
    python tic_tac_toe.py
    ```

## How to Play

1. The game will display a 3x3 grid.
2. Players take turns to enter their move (row and column).
3. The game checks for a win, loss, or draw after each move.
4. The game ends when one player wins or the board is full (draw).

### Example

Below is an example interaction with the game:

```plaintext
 | | 
-----
 | | 
-----
 | | 
Player X, enter the row (0, 1, 2): 0
Player X, enter the column (0, 1, 2): 0
X| | 
-----
 | | 
-----
 | | 
Player O, enter the row (0, 1, 2): 1
Player O, enter the column (0, 1, 2): 1
X| | 
-----
 |O| 
-----
 | | 
...

