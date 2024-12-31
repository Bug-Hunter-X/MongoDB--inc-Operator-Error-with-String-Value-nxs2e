# MongoDB $inc Operator Error

This repository demonstrates a common error when using the `$inc` operator in MongoDB update operations. The `$inc` operator is used to increment or decrement a numerical field in a document.  However, providing a string value instead of a number results in unexpected behavior and potentially incorrect data updates.  The solution shows the correct way to use `$inc` with numerical values.

## Bug
The bug involves using a string value with the `$inc` operator.  This leads to the value being appended as a string instead of incrementing the numerical value.