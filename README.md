# Unexpected Type Coercion in JavaScript Addition

This example demonstrates a common JavaScript pitfall: unexpected type coercion with the addition operator (+).

In JavaScript, the + operator will perform string concatenation if one of the operands is a string. This can lead to unexpected results when adding numbers and strings together. 

The solution involves using explicit type conversion (e.g., parseInt or Number) to ensure that both operands are numbers before performing the addition operation.

## How to Reproduce

1. Save the `bug.js` file.
2. Run the code using a JavaScript interpreter (Node.js, browser's console, etc.).
3. Observe the unexpected output.

## Solution

The `bugSolution.js` demonstrates how to correct the addition operation using type conversion before adding numbers. 