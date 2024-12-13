# MongoDB $inc operator with string value
This example demonstrates an incorrect usage of the MongoDB `$inc` operator, which results in an error. The `$inc` operator is used to increment a numerical field by a specified value. However, in this case, the value is a string, which causes the operation to fail.
The solution is to ensure that the value to increment the field by is a number. 