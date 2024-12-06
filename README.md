# Unexpected String Concatenation in JavaScript

This repository demonstrates a common yet subtle JavaScript bug related to type coercion.  The `foo` function intends to add two numbers, but due to JavaScript's loose typing, it performs string concatenation when one of the inputs is a string.

## Bug Description
The `foo` function should add two numbers. However, it produces unexpected results when one of the inputs is a string because JavaScript converts the number to a string and concatenates them.

## How to Reproduce
1. Clone this repository.
2. Open `bug.js` in a JavaScript environment.
3. Run the code.  Observe the output.

## Solution
The `bugSolution.js` file provides a solution using explicit type checking to ensure both inputs are numbers before performing the addition.