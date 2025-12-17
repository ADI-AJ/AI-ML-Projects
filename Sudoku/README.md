# Sudoku Solver in Python

This project is a Sudoku solver written in Python using backtracking and constraint propagation.  
It loads hard puzzles from `.npy` files, solves them, and compares the result with the provided solutions.

## How it works

- Represents the Sudoku as a 9x9 NumPy array (0 means empty).
- Tracks possible values for each cell.
- Removes impossible values based on row, column, and 3x3 box rules.
- Uses backtracking to try values and undo bad choices.

## Files

- `code.py` – main solver.
- `data/hard_puzzle.npy` – Sudoku puzzles.
- `data/hard_solution.npy` – solutions for checking.
