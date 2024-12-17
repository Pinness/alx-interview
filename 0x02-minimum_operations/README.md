# Minimum Operations

This project involves solving the problem of determining the minimum number of operations required to create exactly `n` characters of `H` in a text editor. The editor supports only two operations: **Copy All** and **Paste**.

## Problem Description

Given an integer `n`, the goal is to calculate the minimum number of operations needed to generate exactly `n` characters of `H` in the editor, starting with a single `H`.

### Operations
1. **Copy All**: Copies the entire content of the text file.
2. **Paste**: Pastes the previously copied content into the file.

### Constraints
- If `n` is impossible to achieve, the function should return `0`.

## Prototype

```python
def minOperations(n):
    """
    Calculate the fewest number of operations needed to result in exactly `n` H characters.

    Args:
        n (int): The target number of H characters.

    Returns:
        int: The minimum number of operations needed, or 0 if impossible.
    """
