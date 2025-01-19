# MongoDB $inc Operator Error with String Value

This repository demonstrates a common error when using the `$inc` operator in MongoDB update queries. The error occurs when attempting to increment a numeric field with a string value.

## Bug
The `bug.js` file contains code that attempts to increment the `count` field of a document using the `$inc` operator with a string value ('1'). This leads to an error because the `$inc` operator expects a numeric value.

## Solution
The `bugSolution.js` file demonstrates the correct usage of the `$inc` operator, providing a numerical value to increment the `count` field.