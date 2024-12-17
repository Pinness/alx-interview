# UTF-8 Validation

This project validates if a given list of integers represents a valid UTF-8 encoding. The validation is done through a function `validUTF8` that checks the given data against the rules of UTF-8 encoding.

## Files

- `0-validate_utf8.py`: Contains the implementation of the `validUTF8` function.
- `0-main.py`: The main testing file that uses the `validUTF8` function to test different sets of data.

## Functionality

The `validUTF8` function takes a list of integers as input, where each integer represents a byte in the UTF-8 encoding. It checks whether these integers form a valid UTF-8 encoded sequence according to the following rules:

- Each byte in the sequence must follow the valid UTF-8 encoding patterns.
- The function returns `True` if the sequence is valid, and `False` otherwise.

