# MongoDB $inc Operator Error
This repository demonstrates a common error encountered when using the `$inc` operator in MongoDB update operations.  The `$inc` operator is used to increment a numerical field by a specified value.  However, attempting to increment with a non-numeric value will result in an error.

## Bug
The `bug.js` file contains code that incorrectly attempts to increment a field using a string value.

## Solution
The `bugSolution.js` file provides the corrected code, using a valid numeric value to increment the field correctly.
