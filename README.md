# Custom Calculator Project

## Overview

The Custom Calculator Project is a Java-based application that implements a versatile calculator with additional features beyond basic arithmetic operations. This repository contains the source code and testing suite for the project.

## Features

### Basic Arithmetic Operations

The calculator supports essential arithmetic operations, including addition, subtraction, multiplication, and division. The implementation ensures accurate and reliable calculations.

### Linear Equation Solver

The project includes a feature to solve simple linear equations of the form ax + b = c, where the user can input coefficients 'a', 'b', and constant 'c' to find the solution for 'x'.

### Custom Mean Calculation

A custom feature allows users to calculate the mean (average) of a set of numbers. The application prompts users to input the number of elements and then accepts the corresponding numeric values, providing the mean as the result.

## Testing

The project places a strong emphasis on testing, with a dedicated test suite (`CalculatorTest.java`) covering various scenarios, edge cases, and error conditions. This ensures the reliability and robustness of the implemented calculator functionalities.

## Usage

To interact with the calculator, users can run the `Calculator.java` class, which serves as the entry point for the application. The `main` method demonstrates the usage of the implemented features, including basic arithmetic, linear equation solving, and custom mean calculation.

## Project Structure

- `src/main/java/com/aslinformationservices/calculator`: Contains the Java classes for the calculator logic.
  - `Calculator.java`: Implements basic arithmetic operations.
  - `EquationSolver.java`: Solves simple linear equations.
  - `CustomFeature.java`: Calculates the mean of a set of numbers.
- `src/test/java/com/aslinformationservices/calculator`: Contains JUnit tests for the calculator logic.
  - `CalculatorTest.java`: Test class for `Calculator.java`.

## Getting Started

1. Ensure Java 11 is installed on your system.
2. Clone or download this repository.
3. Use your preferred IDE or command line to compile and run the Java files.
4. Implement the logic for each method in the provided classes.
5. Run the tests to verify the correctness of your implementation.
