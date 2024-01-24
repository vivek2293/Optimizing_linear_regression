# Linear Regression Optimization with Binary Search

## Overview

This project focuses on optimizing linear regression parameters, specifically the slope and intercept, using binary search to minimize the mean square error. The optimization process involves iteratively updating the parameter values while adjusting the learning rate to reach the global minimum efficiently.

## Initial Data

The initial dataset consists of two arrays:
```python
X = [2, 4, 6, 8]
Y = [3, 7, 5, 10]
```

## Function Descriptions

### `get_new_values`

This function updates the slope (m) and intercept (c) using the given formulas, considering the predicted values.

### `calc_mean_square_error`

Calculates the mean square error for the given linear regression parameters and input data.

### `is_overshooting`

Checks if the new parameter values lead to overshooting by comparing errors.

### Binary Search for Optimization

The optimization process involves initializing parameters, calculating errors, and iteratively updating the values based on the binary search approach. The learning rate (alpha) is adjusted dynamically to optimize convergence.

### Results

Prints the minimum mean square error achieved with a specified tolerance.

### Plotting the Graph

The optimization process is visualized using a scatter plot, where the x-axis represents the slope and the y-axis represents the mean square error.

The project provides insights into how binary search can efficiently converge to the global minimum in linear regression optimization.