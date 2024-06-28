# -PROGIDY_SD_04-

Create a program that solves Sudoku puzzles automatically. The program should take an input grid representing an unsolved Sudoku puzzle and use an algorithm to fill in the missing numbers.
It should use backtracking or other suitable techniques to explore possible solutions and find the correct arrangement of numbers for the puzzle. Once solved, the program should display the completed Sudoku grid.


Explanation:
Print Board: The print_board function displays the Sudoku board, replacing zeros with dots for better readability.
Find Empty Location: The find_empty_location function searches for the next empty cell (represented by a zero) in the board.
Check Validity: The is_valid function checks if a number can be placed in a specified position without violating Sudoku rules (row, column, and 3x3 box constraints).
Solve Sudoku: The solve_sudoku function uses backtracking to solve the Sudoku puzzle. It fills numbers recursively and backtracks if it encounters a conflict.
Main Function: The main function initializes an example Sudoku puzzle, prints the unsolved board, calls the solver, and prints the solved board if a solution exists.
