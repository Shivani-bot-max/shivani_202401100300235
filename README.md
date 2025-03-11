# shivani_202401100300235
N-Queens Problem Solver

Overview

The N-Queens problem is a classic combinatorial problem where N queens must be placed on an N×N chessboard so that no two queens attack each other. This program uses backtracking to find a valid solution.

Features

Solves the N-Queens problem for user-provided values of N.

Uses randomized column selection for diversity in solutions.

Prints a valid chessboard arrangement if a solution exists.

Displays an error message if no solution is possible.

How It Works

The program prompts the user to input three different values of N.

For each value of N:

It initializes an empty N×N board.

It applies backtracking to place queens safely.

If a solution is found, it prints the board.

If no solution exists, it notifies the user.

Usage

Run the script and input values for N when prompted. Example:

Enter the value of N for the N-Queens problem (attempt 1/3): 4
Enter the value of N for the N-Queens problem (attempt 2/3): 8
Enter the value of N for the N-Queens problem (attempt 3/3): 6

Output Example

For N = 4, the output might look like:

Solving 4-Queens problem:
. Q . .
. . . Q
Q . . .
. . Q .

Each Q represents a queen, and . represents an empty space.

Requirements

Python 3.x

No external dependencies

Author

This program was developed as an implementation of the N-Queens backtracking algorithm with randomized column selection.

