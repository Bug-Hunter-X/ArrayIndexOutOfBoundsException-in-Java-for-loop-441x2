# ArrayIndexOutOfBoundsException Bug in Java

This repository demonstrates a common error in Java: the `ArrayIndexOutOfBoundsException`.  The bug arises from a simple off-by-one error in a `for` loop that iterates over an array.

## Bug Description

The `bug.java` file contains a Java program that initializes an integer array and then attempts to populate and access it using a `for` loop. The loop's termination condition is incorrect, leading to an attempt to access an element beyond the array's bounds.

## Solution

The `bugSolution.java` file corrects the error by adjusting the loop condition to correctly iterate within the array's boundaries.  This prevents the `ArrayIndexOutOfBoundsException`.

## How to Reproduce

1. Clone this repository.
2. Compile and run `bug.java`. Observe the `ArrayIndexOutOfBoundsException`. 
3. Compile and run `bugSolution.java`. Observe the successful execution and correct output.