# JavaScript Type Coercion Bug

This repository demonstrates a common type coercion issue in JavaScript where the `+` operator performs string concatenation when one operand is a string, even if the other is a number.  The `bug.js` file shows the unexpected behavior, while `bugSolution.js` demonstrates a solution.

## Bug Description

The `foo` function is expected to perform numerical addition. However, due to JavaScript's loose typing and how the `+` operator handles type coercion, the output is unexpected string concatenation.

## Solution

The `bugSolution.js` file provides a solution using explicit type conversion (using `parseInt` or `Number`) to ensure numerical addition.  Alternative solutions might include using template literals for string formatting if string concatenation was intended.