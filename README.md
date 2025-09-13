# Build-Sudoku-Game-in-Cpp
The Sudoku Game project is a console-based implementation of the popular Sudoku puzzle, developed in C++.

## Brief
1. Console Application
o Upon running, display the Sudoku puzzle (9×9), using a dot . for empty cells.
3
o Offer a menu with options (e.g., enter a move, solve automatically, load/save puzzle, exit).
2. Board Operations
o Load an initial puzzle into a 9×9 matrix (e.g., from a hard-coded array or a file).
o Check validity of user moves (row/column/3×3 constraints).
o Set a value in the puzzle if valid.
o Print the board in a neat ASCII format.
3. Solving
o Backtracking Solver: Attempt to fill remaining cells and complete the puzzle.
4. Menu & Error Handling
o Enter a Move: 
1. Ask for row, column, and value (1–9).
2. Validate integer input and range.
3. If invalid, print error message. Otherwise, place the value in the board.
o Solve Automatically: 
1. Trigger the solver and display the completed board or an error if unsolvable.
o Load From File (Optional): 
1. Reads a file containing a 9×9 puzzle.
o Save To File (Optional): 
1. Writes the current board to a file.
o Exit: End the application safely.
