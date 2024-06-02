This Python program offers a user-friendly interface for generating and solving Sudoku puzzles of varying difficulty levels (Easy, Medium, Hard). It utilizes backtracking algorithm to efficiently solve the generated puzzles. The _generate_partial_sudoku function creates a partially filled Sudoku grid based on the specified difficulty level, incorporating random shuffling to ensure uniqueness. The print_sudoku function neatly formats and prints the Sudoku grid to the console. Validity of moves is ensured by the is_valid_move function, which checks for violations of Sudoku rules. The solve_sudoku function recursively solves the puzzle using backtracking, iterating through each empty cell and attempting numbers from 1 to 9 until a solution is found. In the main function, users select a difficulty level, and a Sudoku puzzle is generated and printed. They are then given the option to view the solution, which is displayed if requested. Overall, the program provides an engaging experience for Sudoku enthusiasts, offering both puzzle generation and solution capabilities within a single interface.

Welcome to Sudoku Generator!
Choose difficulty (Easy, Medium, Hard): easy
Generated Sudoku Puzzle:
+_______+_______+_______+
| 3 . . | 5 8 2 | . . 1 |
| . 1 7 | 6 9 . | 8 5 2 |
| . . 8 | . . 4 | 9 . 3 |
+_______+_______+_______+
| . 3 9 | . . . | . 7 4 |
| . . 1 | . . 6 | 2 . 5 |
| . 5 2 | . 4 7 | . . 6 |
+_______+_______+_______+
| . . . | . . 8 | 4 1 . |
| 1 . 4 | . 6 . | 5 . 8 |
| 2 8 . | . . . | . 3 9 |
+_______+_______+_______+
Do you want to see the solution? (yes/no): yes
Sudoku Solution:
+_______+_______+_______+
| 3 9 6 | 5 8 2 | 7 4 1 |
| 4 1 7 | 6 9 3 | 8 5 2 |
| 5 2 8 | 7 1 4 | 9 6 3 |
+_______+_______+_______+
| 6 3 9 | 8 2 5 | 1 7 4 |
| 7 4 1 | 9 3 6 | 2 8 5 |
| 8 5 2 | 1 4 7 | 3 9 6 |
+_______+_______+_______+
| 9 6 3 | 2 5 8 | 4 1 7 |
| 1 7 4 | 3 6 9 | 5 2 8 |
| 2 8 5 | 4 7 1 | 6 3 9 |
+_______+_______+_______+

=== Code Execution Successful ===
