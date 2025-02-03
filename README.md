# Incorrect Usage of $inc Operator in MongoDB
This example demonstrates an incorrect usage of the `$inc` operator in MongoDB. The `$inc` operator is designed to increment a numeric field by a specified value.  However, the code attempts to increment a field using a string value. This leads to an error because the $inc operator only works with numerical values.  The solution provided shows how to correct this by passing a numerical value to the $inc operator.  This repository shows best practice use of the $inc operator with both correct and incorrect examples.