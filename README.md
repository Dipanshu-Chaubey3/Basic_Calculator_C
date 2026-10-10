# Basic Calculator in C

A small console calculator that supports addition, subtraction, multiplication, and division.

## Requirements
- GCC or another C compiler

## Compile and run
```bash
gcc -Wall -Wextra -Wpedantic calculator.c -o calculator
# Windows: .\calculator.exe
# macOS/Linux: ./calculator
``

The program validates numeric input, rejects unknown operators, and prevents division by zero.

## Example
```text
Enter first number: 8
Enter an operator (+, -, *, /): /
Enter second number: 2
8.00 / 2.00 = 4.00
``
