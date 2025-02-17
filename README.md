# Python ZeroDivisionError in Average Calculation

This repository demonstrates a common error in Python: the `ZeroDivisionError` that can occur when calculating the average of an empty list.  The original code lacks proper error handling.  The solution demonstrates how to gracefully handle this edge case.

## Bug
The `calculate_average` function does not check for an empty input list before performing the division operation, which leads to a `ZeroDivisionError` if the list is empty.

## Solution
The solution adds a check for an empty list at the beginning of the function. If the list is empty, it returns 0 (or any other appropriate default value) to prevent the error.