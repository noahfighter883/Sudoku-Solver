# Sudoku Solver (Python)

Backtracking-based Sudoku solver implemented in Python, demonstrating recursive search, constraint validation, and algorithmic problem solving.

## Overview

This project implements a classic Sudoku solver using a depth-first backtracking algorithm. The solver fills a partially completed 9x9 Sudoku grid while enforcing row, column, and subgrid constraints.

The goal of the project is to demonstrate recursive reasoning, constraint checking, and clean algorithmic design.

## Features

- Solves standard 9x9 Sudoku puzzles
- Validates row, column, and 3x3 subgrid constraints
- Uses recursive backtracking search
- Console-based output

## Algorithm

The solver follows this process:

1. Locate the next empty cell.
2. Try digits 1–9.
3. Check whether the digit satisfies:
   - Row constraint
   - Column constraint
   - 3x3 subgrid constraint
4. Recursively continue if valid.
5. Backtrack if a conflict occurs.

Time complexity is exponential in the worst case, but performs efficiently for standard puzzle difficulty levels.

## How to Run

```bash
python sudoku.py
