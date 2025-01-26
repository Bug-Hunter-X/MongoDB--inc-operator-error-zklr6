# MongoDB $inc operator error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment or decrement a numeric field by a specified value. However, if a non-numeric value is provided, it will result in an error.

## Bug
The original code incorrectly uses a string value '1' with `$inc` operator.

## Solution
The solution is to provide a numeric value to the `$inc` operator.
