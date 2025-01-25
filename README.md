# Unexpected Null Return in Addition Function

This repository demonstrates a common JavaScript error involving unexpected null returns in a seemingly simple addition function.

## The Bug
The `foo` function is designed to add two numbers. However, it returns `null` if either input is `null`. This behavior might be unexpected if you need the function to handle null values in a specific way (e.g., treat them as 0).

## The Solution
The solution involves explicitly handling `null` values by replacing them with 0 before performing the addition. This ensures the function always returns a numerical result, regardless of null inputs.

## How to Run
1. Clone this repository.
2. Open `bug.js` to see the buggy code.
3. Open `bugSolution.js` to see the corrected code.
4. Run each file in a JavaScript environment (e.g., Node.js) to observe the outputs.