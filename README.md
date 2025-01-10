# Unhandled Modulo Operator in Calculator Function

This repository demonstrates a common bug in JavaScript related to the unhandled modulo operator (%) in a simple calculator function.

## Description

The provided JavaScript code implements a basic calculator with functions for addition, subtraction, multiplication, and division. However, it lacks handling for the modulo operator (%).  This can lead to unexpected errors or incorrect results when attempting to use the modulo operation.

## Bug

The `operate` function, which handles calculations, doesn't include a case for the `%` operator.  If the user tries to use this operator, the function throws a generic "Invalid operator" error.

## Solution

The solution involves adding a case within the `switch` statement to handle the modulo operator.  This will allow the code to perform modulo operations correctly.

## How to Run

1. Clone the repository.
2. Open the `bug.js` file to see the buggy code.
3. Open the `bugSolution.js` file to see the corrected code.
4. Run each file using a JavaScript interpreter (like Node.js).