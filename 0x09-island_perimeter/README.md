# 0x09 - Island Perimeter

This directory contains a Python solution for the "Island Perimeter" problem.

## Task Description

Write a function `def island_perimeter(grid):` that calculates the perimeter of the island described in a grid.

### Requirements:
- **grid** is a list of lists of integers.
- `0` represents water.
- `1` represents land.
- Each cell is square with a side length of 1.
- Cells are connected horizontally/vertically (not diagonally).
- The grid is rectangular, with its width and height not exceeding 100.
- The grid is completely surrounded by water.
- There is only one island (or no island).
- The island doesn’t have lakes (water inside that isn’t connected to the water surrounding the island).

## Example Usage

**Input Grid:**
```python
grid = [
    [0, 0, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 0, 0, 0, 0],
    [0, 1, 1, 1, 0, 0],
    [0, 0, 0, 0, 0, 0]
]
