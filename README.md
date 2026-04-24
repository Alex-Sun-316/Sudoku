# Sudoku Solver

A Python-based 9x9 Sudoku solver built using rule-based constraint propagation.
Here is the demo  https://alex-sun-316.github.io/sudoku-demo/
## Overview
This project represents a Sudoku board as a 9x9 grid of candidate sets and solves the puzzle by repeatedly eliminating invalid values based on Sudoku constraints.

For each cell, the solver removes impossible values using:
- row constraints
- column constraints
- 3x3 subgrid constraints

If a cell is reduced to a single value, that value is propagated to related cells until no more updates can be made.

## Features
- Represents each cell as a set of possible values
- Supports loading Sudoku boards from string input
- Performs candidate elimination through constraint propagation
- Detects invalid or unsolvable board states
- Displays both simplified and detailed board views

## Technologies
- Python
- Object-oriented programming
- Constraint propagation

## Project Structure
- `Sudoku_Solver.ipynb` — main notebook containing the solver implementation and test cases
- `README.md` — project description
