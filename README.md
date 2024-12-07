# JavaScript Bug: TypeError: Cannot read properties of undefined (reading 'length')

This repository demonstrates a common JavaScript error: `TypeError: Cannot read properties of undefined (reading 'length')`.  The bug occurs when attempting to access the `length` property of a variable that is `undefined`.

The `bug.js` file contains the erroneous code, while `bugSolution.js` provides a corrected version.

## Bug:

The original code attempts to access the `length` property of a variable `x` without first checking if it is `undefined`. If `x` is `undefined`, this will throw the error.

## Solution:

The corrected code explicitly checks for both `null` and `undefined` before accessing the `length` property, preventing the error.
