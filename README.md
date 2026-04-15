# Sudoku-Project, TEJ NANDLAL
This program creates a fully solved 9×9 Sudoku board and prints it out in a clean grid format. It uses a 2D array to store the board and fills it using a simple shifting pattern with the numbers 1 through 9. Instead of manually typing in a finished puzzle, the program builds the board step by step by rearranging the base numbers in a consistent way for each row. Once the board is complete, it is printed in an organized layout with clear lines separating the 3×3 sections.

Open the file SudokuGenerator.java in CodeHS and run the program. It will automatically execute the main method and print a completed Sudoku board.

The program creates a 9×9 two-dimensional array to represent the Sudoku board. It uses an ArrayList containing the numbers 1 through 9 as a base pattern. Each row of the board is filled using a shifting formula based on the row number, which rearranges the base list in a consistent pattern. This ensures every row contains the numbers 1 through 9 without repetition. The process repeats for all rows until the entire board is filled, resulting in a completed Sudoku solution generated using logic instead of hardcoded values.

Files:

SudokuGenerator.java https://codehs.com/sandbox/id/java-main-X04MNy?filepath=SudokuGenerator.java (Main program code)
, README.md (This)
, Design document file (2 page doc)
