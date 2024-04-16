# Numerical Calculator

The Numerical Calculator is a Java-based application that provides various numerical analysis functionalities. It allows users to perform calculations related to integration, finding roots, solving systems of linear equations, interpolation, inverse interpolation, and solving ordinary differential equations.

## Features

The calculator provides the following functionalities:

1. Integration: Calculates the definite integral of a given function using Simpson's 3/8 rule.
2. Find Root: Finds the root of a given function using the bisection method.
3. Equation Solve 2X2: Solves a system of two linear equations using Gaussian elimination.
4. Equation Solve 3X3: Solves a system of three linear equations using Gaussian elimination.
5. Interpolation: Performs Lagrange interpolation to estimate the value of a function at a specific point.
6. Inverse Interpolation: Estimates the input value of a function given its output value using Lagrange interpolation.
7. Solve Ordinary Diff. Eqn.: Solves a first-order ordinary differential equation using the Euler method.

## Getting Started

To run the Numerical Analysis Calculator, follow these steps:

1. Ensure you have Java Development Kit (JDK) installed on your machine.
2. Clone or download the project repository from GitHub.
3. Open the project in your preferred Java development environment (e.g., Apache NetBeans, Eclipse).
4. Compile and run the `CalculatorMain.java` file to launch the calculator application.
5. The graphical user interface will appear, providing buttons for each functionality.
6. Click on the respective buttons to perform the desired numerical analysis calculation.
7. Input the required parameters or equations in the text display area.
8. View the calculated results in the text display area by clicking '=' button .

## Dependencies

The Numerical Analysis Calculator utilizes the following dependencies:

- `javax.swing`: Provides the graphical user interface components for the calculator.
- `net.objecthunter.exp4j`: Used for parsing and evaluating mathematical expressions.

These dependencies are already included in the project's `pom.xml` file and will be automatically downloaded if you are using a Maven-based build system.

## Contributing

Contributions to the Numerical Analysis Calculator project are welcome! If you have any suggestions, bug reports, or feature requests, please create an issue on the project's GitHub repository.

## Acknowledgments

The Numerical Analysis Calculator project is inspired by the concepts and algorithms taught in numerical analysis courses. Special thanks to the developers and contributors of the libraries used in this project for their excellent work.
