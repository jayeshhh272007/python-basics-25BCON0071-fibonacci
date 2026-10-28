# README Claims Audit — Fibonacci Sequence

## 1. Program Purpose
**Claim:** The program generates the Fibonacci sequence for a specified number of terms.

**Status:** Supported

**Evidence:** The program takes the number of terms as input and uses a loop to print the Fibonacci sequence.

## 2. User Input
**Claim:** The program takes the number of terms as input.

**Status:** Supported

**Evidence:** The statement `n = int(input("Enter the number of terms: "))` accepts the number of terms from the user.

## 3. Initialization
**Claim:** The program initializes the first two values as 0 and 1.

**Status:** Supported

**Evidence:** The statement `a, b = 0, 1` initializes the sequence.

## 4. Loop Implementation
**Claim:** The program uses a loop to print each term.

**Status:** Supported

**Evidence:** The `for i in range(n):` loop runs `n` times and prints the current value of `a`.

## 5. Sequence Generation
**Claim:** The program updates the values to generate the next term.

**Status:** Supported

**Evidence:** The statement `a, b = b, a + b` updates the variables to generate the next Fibonacci number.

## 6. Example Output
**Claim:** For input `7`, the output is `0 1 1 2 3 5 8`.

**Status:** Supported

**Evidence:** The loop prints seven Fibonacci terms, beginning with 0 and 1.

## 7. Learning Objectives
**Claim:** The program demonstrates Python variables, user input, loops, and updating values to generate a sequence.

**Status:** Supported

**Evidence:** The code uses `input()`, variables `n`, `a`, and `b`, a `for` loop, and simultaneous assignment.

## Conclusion
All claims reviewed above are supported by the Fibonacci program provided for this audit. No unsupported claims were identified.
