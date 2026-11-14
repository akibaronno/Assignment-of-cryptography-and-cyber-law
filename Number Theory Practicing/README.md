# Day 1 Assignment — Number Theory and Modular Arithmetic

This repository contains a Jupyter Notebook assignment focused on implementing fundamental number-theory algorithms using Python.

## Overview

The notebook contains six programming problems. The main goal is to understand how these algorithms work and implement them efficiently.

## Assignment Tasks

1. **Extended Euclidean Algorithm**
   - Implement `extended_gcd(a, b)`.
   - Return `(d, x, y)`, where `d = GCD(a, b)` and `d = a*x + b*y`.

2. **Least Common Multiple (LCM)**
   - Implement `lcm(a, b)` for two positive integers.
   - Use the relationship between GCD and LCM to develop an efficient solution.

3. **Linear Diophantine Equation**
   - Implement `diophantine(a, b, c)`.
   - Find integers `x` and `y` satisfying `a*x + b*y = c`, assuming a solution exists.

4. **Modular Inverse and Modular Division**
   - Implement `modInverse(a, n)` using the Extended Euclidean Algorithm.
   - Complete the provided `divide(b, a, n)` workflow to find `x` such that `a*x ≡ b (mod n)`.

5. **Fast Modular Exponentiation**
   - Implement `FastModularExponentiation(b, e, m)`.
   - Compute `b^e mod m` efficiently without using Python's built-in exponentiation operation.
   - The target is approximately `2 log₂(e)` modular multiplications.

6. **Chinese Remainder Theorem (CRT)**
   - Implement `ChineseRemainderTheorem(n1, r1, n2, r2)`.
   - Find the unique integer `r` in the range `0 ≤ r < n1*n2` satisfying both given congruences, where `n1` and `n2` are distinct coprime integers.

## Concepts Covered

- Greatest Common Divisor (GCD)
- Extended Euclidean Algorithm
- Bézout's identity
- Least Common Multiple (LCM)
- Linear Diophantine equations
- Modular arithmetic
- Multiplicative modular inverse
- Modular division
- Fast modular exponentiation (exponentiation by squaring)
- Chinese Remainder Theorem

## Project Structure

```text
.
└── Day 1 Assignment.ipynb
```

## Requirements

- Python 3
- Jupyter Notebook or JupyterLab

The assignment uses standard Python functionality and does not require additional third-party libraries.

## How to Run

1. Clone or download this repository.
2. Open a terminal in the project directory.
3. Start Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   Or start JupyterLab:

   ```bash
   jupyter lab
   ```

4. Open `Day 1 Assignment.ipynb`.
5. Implement each function in the cells marked `YOUR CODE HERE`.
6. Run the notebook cells in order and check the provided assertions and sample test cases.

## Important Notes

- Do not remove or modify the provided assertions in the assignment templates.
- Implement your solutions only in the designated sections.
- Run the `extended_gcd` implementation before running problems that depend on it, such as modular inverse and the Chinese Remainder Theorem.
- The uploaded notebook is an assignment template: the function bodies contain `YOUR CODE HERE` / `NotImplementedError()` placeholders. Complete implementations are not included in the starter notebook.

## Learning Objective

By completing this assignment, you will gain practical experience implementing core number-theory algorithms and understand how they are used in modular arithmetic and related computational problems.
