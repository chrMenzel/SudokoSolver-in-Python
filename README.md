# SudokoSolver-in-Python

A pyton program to solve a Sudoku.

## Usage:

Run `sudoku.py` in console or in your IDE to see the result of the follwing sudoku problem:

```
6 . . | . . . | 3 . .
9 . . | 4 7 . | 1 . .
7 . . | 9 5 . | . . .
------+-------+------
. . . | 3 9 . | . . .
. 3 . | . . . | . . 2
. 2 . | . . . | 8 . 4
------+-------+------
. . 6 | 2 . 1 | . . .
. . . | . . . | 6 4 5
4 . 8 | . . . | . . .
```

The internal call of the problem above looks as follows:
`display(search('6.....3..9..47.1..7..95.......39.....3......2.2....8.4..62.1.........6454.8......'))`

The search string is written all 9 lines of the problem in one row without any spaces or delimiters.

Currently you can only change the search string in the code itself to solve another sudoku problem.

## Planning:
A GUI to make this program more user-friendly.
