# Matrix-Statistics
The input of the function should be a list containing 9 digits. The function should convert the list into a 3 x 3 Numpy array, and then return a dictionary containing the mean, variance, standard deviation, max, min, and sum along both axes and for the flattened matrix.


# Mean-Variance-Standard Deviation Calculator

This project is a Python program that calculates the **mean**, **variance**, **standard deviation**, **max**, **min**, and **sum** of the rows, columns, and all elements of a 3x3 matrix. It uses **NumPy** for efficient array operations.

## Project Overview

The function `calculate()` takes a list of 9 numbers as input, converts it into a 3x3 NumPy array, and returns a dictionary with the calculated statistics for each axis (rows and columns) as well as for the entire flattened matrix.

### Example Input:

```python
calculate([0, 1, 2, 3, 4, 5, 6, 7, 8])
```

Features
1-Converts a list of 9 numbers into a 3x3 matrix.
2-Computes statistics along both axes (rows and columns) and for the entire matrix.
3-Handles invalid inputs by raising a ValueError if the input list does not contain exactly 9 elements.


Technologies Used
1-Python: For the core implementation.
2-NumPy: Used for efficient matrix operations and statistical calculations.

Function Details
calculate(lst)
--  Input: A list of 9 numerical values.
--  Output: A dictionary with the following keys:
1-'mean': Mean values along axis 0, axis 1, and flattened matrix.
2-'variance': Variance values along axis 0, axis 1, and flattened matrix.
3-'standard deviation': Standard deviation values along axis 0, axis 1, and flattened matrix.
4-'max': Maximum values along axis 0, axis 1, and flattened matrix.
5-'min': Minimum values along axis 0, axis 1, and flattened matrix.
6-'sum': Sum values along axis 0, axis 1, and flattened matrix.

Error Handling
-- If the input list does not contain exactly 9 elements, the function raises a ValueError with the message: "List must contain nine numbers."
