# MongoDB $inc Operator with String Value

This example demonstrates an uncommon error when using the `$inc` operator in MongoDB update queries. The `$inc` operator is designed to increment numeric fields, and using it with a string value will lead to an error.

The `bug.js` file shows the erroneous code, while `bugSolution.js` provides the corrected implementation.