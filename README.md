# Tic-Tac-Toe

## Description

This project is a console-based Tic-Tac-Toe game developed in C++. The game allows a human player to compete against the computer on a 3×3 grid. The program validates moves, updates the board after each turn, and determines the winner by checking rows, columns, and diagonals.

## Features

- Human vs Computer gameplay
- Winner detection
- Draw detection
- Input validation
- Multiple game sessions

## Technologies Used

- C++
- Standard Template Library (STL)

## How to Run

1. Compile the source code:

```bash
g++ tic_tac_toe.cpp -o tic_tac_toe
```

2. Run the executable:

```bash
./tic_tac_toe
```

## Game Rules

- The human player uses **X**.
- The computer uses **O**.
- The first player to align three symbols in a row, column, or diagonal wins.
- If all cells are filled without a winner, the game ends in a draw.

## Project Structure

- `showBoard()` – Displays the game board.
- `showInstructions()` – Displays game instructions.
- `initialise()` – Initializes the board.
- `bestMove()` – Determines the computer's move.
- `minimax()` – Evaluates possible moves.
- `playTicTacToe()` – Controls game flow.

## Conclusion

This project demonstrates the use of arrays, functions, loops, recursion, and basic game logic in C++. It provides an interactive implementation of the classic Tic-Tac-Toe game.
