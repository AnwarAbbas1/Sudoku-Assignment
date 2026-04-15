Sudoku CSP Solver (Backtracking + AC-3)

Overview
This project is a Sudoku solver implemented using Constraint Satisfaction Problem (CSP) techniques. It uses backtracking search combined with constraint propagation (AC-3) to efficiently solve Sudoku puzzles of different difficulty levels.

Features

Solves Sudoku puzzles: Easy, Medium, Hard, Very Hard
Backtracking search with failure tracking
Constraint propagation to reduce search space
Counts backtracking calls and failures
Reads puzzles from text files
Displays input board and final solution clearly
Includes difficulty-based performance insights

Files

main.py → main driver program
easy.txt → Easy puzzle input
medium.txt → Medium puzzle input
hard.txt → Hard puzzle input
veryhard.txt → Very hard puzzle input

How It Works

Reads Sudoku board from file
Prints the initial puzzle
Solves using CSP backtracking + AC-3
Tracks backtracking calls and failures
Prints solution (if found)
Displays performance comments based on difficulty

Output Example
For each puzzle, the program shows:

Puzzle name (difficulty level)
Input board
Solved board (if solvable)
Backtracking statistics
Performance explanation

Algorithm Used

Backtracking Search
AC-3 (Arc Consistency Algorithm)

Author
Anwar Abbas
Roll No: 23F-0848