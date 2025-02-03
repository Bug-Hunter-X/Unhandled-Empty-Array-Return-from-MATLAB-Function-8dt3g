# Unhandled Empty Array Return from MATLAB Function

This repository demonstrates a common yet subtle issue in MATLAB: functions returning empty arrays without explicit handling in the calling code.  This can lead to unexpected behavior, especially within loops or when the empty array is used in further calculations.

The `bug.m` file contains a function that, under certain conditions, returns an empty array ([]). The calling code does not effectively check for this condition, which can result in problems.

The `bugSolution.m` file shows a corrected version with improved error handling.