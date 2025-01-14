# JavaScript subtle bug: Null and Undefined in Arithmetic

This repository demonstrates a common yet easily missed bug in JavaScript related to how the language handles `null` and `undefined` values within arithmetic operations.

The `bug.js` file contains a function `foo` that attempts to add two numbers. However, it doesn't correctly handle cases where one or both of the inputs are `null` or `undefined`. This leads to unexpected results, particularly `NaN` (Not a Number).

The `bugSolution.js` file provides a corrected version of the function, showcasing how to handle `null` and `undefined` inputs effectively to avoid the `NaN` issue.

This example highlights the importance of robust input validation and handling in JavaScript to ensure predictable and error-free code.