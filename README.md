# JavaScript Null Handling Bug

This repository demonstrates a common error in JavaScript: incorrect handling of null values in a function that performs addition. The `foo` function is designed to add two numbers, but it does not properly handle cases where one or both inputs are null. This can lead to unexpected results or runtime errors.

## Bug
The original code does not explicitly check for null values before performing the addition.  This results in unexpected behavior when null is passed as an argument, potentially leading to runtime errors or incorrect output.

## Solution
The solution implements explicit null checks before performing the addition. If either input is null, the function returns null to avoid errors or unintended behavior. This ensures the function handles null values gracefully and returns predictable results.

## How to Run
1. Clone the repository.
2. Open `bug.js` and `bugSolution.js` in a code editor.
3. Run the JavaScript files in a browser's console or a Node.js environment.