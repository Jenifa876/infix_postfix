# Infix to Postfix Converter

This project contains a C++ implementation of a stack data structure that converts infix expressions into postfix expressions using the Shunting Yard algorithm.

## Features

- Supports alphabetic and numeric operands.
- Handles basic operators: `+`, `-`, `*`, `/`, and exponentiation (`^`).
- Manages operator precedence and associativity.
**Code Explanation**
Class Stack: Implements a stack with push, pop, peek, and isEmpty functions.
preced: Returns the precedence of operators.
associ: Determines the associativity of operators.
in_post: Converts an infix expression to a postfix expression.
