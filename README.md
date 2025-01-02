# COBOL Null Pointer Exception Handling

This repository demonstrates a common error in COBOL programs: improper handling of null or empty values.  The `bug.cob` file shows a problematic approach to handling customer names, while `bugSolution.cob` demonstrates a better solution.

## Problem
The original code lacks explicit checks for null or empty values and might fail when CUSTOMER-NAME-IN is missing data. This often leads to unexpected behavior or crashes, especially in older COBOL environments.

## Solution
The improved code uses a more robust check to handle these cases, preventing unexpected errors and improving the reliability of the program.  The solution uses a more structured approach to ensure all possible scenarios are addressed.