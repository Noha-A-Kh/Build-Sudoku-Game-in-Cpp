# Build-Sudoku-Game-in-Cpp ;)
The Sudoku Game project is a console-based implementation of the popular Sudoku puzzle, developed in C++.

## Brief
1. Console Application
    -  Upon running, display the Sudoku puzzle (9×9), using a dot . for empty cells.
    -  Offer a menu with options (e.g., enter a move, solve automatically, load/save puzzle, exit).
    
3. Board Operations
    - Load an initial puzzle into a 9×9 matrix (e.g., from a hard-coded array or a file).
    - Check validity of user moves (row/column/3×3 constraints).
    - Set a value in the puzzle if valid.
    - Print the board in a neat ASCII format.

4. Solving
    - Backtracking Solver: Attempt to fill remaining cells and complete the puzzle.

6. Menu & Error Handling
   - Enter a Move:
       - Ask for row, column, and value (1–9).
       - Validate integer input and range.
       - If invalid, print error message. Otherwise, place the value in the board.
         
    - Solve Automatically:
        - Trigger the solver and display the completed board or an error if unsolvable.
          
   - Load From File (Optional):
         - Reads a file containing a 9×9 puzzle.
   
    - Save To File (Optional):
         - Writes the current board to a file.
           
    - Exit: End the application safely.
