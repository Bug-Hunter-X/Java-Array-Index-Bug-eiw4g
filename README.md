# Java Off-by-One Array Error

This repository demonstrates a classic off-by-one error in Java array manipulation. The code attempts to access an array element beyond its declared size, resulting in an `ArrayIndexOutOfBoundsException`. The solution illustrates how to correct the loop condition to prevent this issue.

## Bug
The `bug.java` file contains the erroneous code.  The loop condition `i <= arr.length` is incorrect; it should be `i < arr.length`.

## Solution
The `bugSolution.java` file provides a corrected version of the code, resolving the off-by-one error and preventing the exception.