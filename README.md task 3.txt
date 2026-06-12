# Sudoku Solver

## Description
This project is a Python-based Sudoku Solver that uses the Backtracking Algorithm to automatically solve Sudoku puzzles. The program takes an unsolved Sudoku grid as input and fills in all empty cells with valid numbers.

## Features
- Solves standard 9x9 Sudoku puzzles
- Uses Backtracking Algorithm
- Displays the solved Sudoku grid
- Easy to understand and modify

## Requirements
- Python 3.x
- Visual Studio Code (optional)

## How to Run

1. Clone or download the project.
2. Open the project folder in VS Code.
3. Open Terminal.
4. Run the following command:

```bash
python sudoku_solver.py
```

## Input Format

Use `0` for empty cells.

Example:

```python
board = [
    [5,3,0,0,7,0,0,0,0],
    [6,0,0,1,9,5,0,0,0],
    [0,9,8,0,0,0,0,6,0],
    [8,0,0,0,6,0,0,0,3],
    [4,0,0,8,0,3,0,0,1],
    [7,0,0,0,2,0,0,0,6],
    [0,6,0,0,0,0,2,8,0],
    [0,0,0,4,1,9,0,0,5],
    [0,0,0,0,8,0,0,7,9]
]
```

## Algorithm Used
Backtracking Algorithm

Steps:
1. Find an empty cell.
2. Try numbers 1 to 9.
3. Check if the number is valid.
4. Recursively solve the remaining puzzle.
5. Backtrack if no valid number is found.

## Output

The program prints the solved Sudoku puzzle in the terminal.

## Author
Shivam Sonnepatil