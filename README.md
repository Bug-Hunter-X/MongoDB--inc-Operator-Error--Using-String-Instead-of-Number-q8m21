# MongoDB $inc Operator Error: Using String Instead of Number

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is designed to increment a numeric field by a specified value.  Attempting to use a string value will result in an error or unexpected behavior.

## Bug
The `bug.js` file contains code that incorrectly uses a string value ('1') with the `$inc` operator. This will lead to a MongoDB error.

## Solution
The `bugSolution.js` file demonstrates the correct usage, providing a numerical value (1) to the `$inc` operator for proper field incrementation.
