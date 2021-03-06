# Sudoku
CSE20212 Lab 5 

Sudoku is a popular puzzle where a player completes a grid (see below) based on some
(but not all) cells provided. The challenge is to find the values of the unknown cells.

Rules:
A traditional Sudoku puzzle is either a 4x4, 9x9 or 16x16 grid. In the case of a 9x9
numeric puzzle, a solved puzzle has the following three properties:
• Every column contains the symbols 1–9 exactly once
• Every row contains the symbols 1–9 exactly once
• Each of the 3x3 minigrids contains the symbols 1–9 exactly once.Over the next two weeks, we will implement simple but generic Sudoku code (this lab)
and develop a solving algorithm with the help of the STL (Lab 6).
Input format for lab:
Puzzles will be composed of 9 lines, each of which contains 9 values separated by a
space. For purposes of our software, values are either 1–9 (filled) or 0 (empty).
A sample puzzle based on Figure 1 (previous page) is encoded below:

0 3 2 0 0 8 9 1 4

0 0 0 0 0 0 0 0 3

0 0 7 1 0 0 0 2 6

0 0 8 0 7 6 0 0 0

9 2 1 3 0 0 0 8 7

0 6 0 0 0 0 4 0 0

0 0 0 0 0 0 0 0 0

0 0 0 0 4 0 5 0 8

8 0 0 6 0 7 0 0 0 
