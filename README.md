# Calculator Project
A simple Java-based Calculator that performs basic arithmetic operations. This project is used for the SWE 472 Software Testing and Quality Assurance course to demonstrate systematic test design, Input Space Partitioning (ISP), and Graph Coverage Criteria.

## Features
The calculator supports:
- Addition
- Subtraction
- Multiplication
- Division (with handling for division by zero)

## Project Structure
```
Calculator/
│
├── src/
│   └── Calculator.java
│
└── test/
    └── CalculatorTest.java
```

## Calculator Class
```java
public class Calculator {
    public double add(double a, double b) {
        return a + b;
    }
    public double subtract(double a, double b) {
        return a - b;
    }
    public double multiply(double a, double b) {
        return a * b;
    }
    public double divide(double a, double b) {
        if (b == 0) {
            throw new IllegalArgumentException("Cannot divide by zero");
        }
        return a / b;
    }
}
```

## Testing
The project demonstrates:
- Input Space Partitioning (ISP)
- Node and Edge Coverage
- Automated unit testing using JUnit

## How to Run
1. Open the project in Eclipse or any Java IDE.
2. Compile the project.
3. Run the Calculator class or the test suite.

## Purpose
This project is part of SWE 472 to practice:
- Designing testable software
- Creating meaningful test partitions
- Performing control flow analysis
- Automating tests and evaluating coverage

## License
This project is for educational use.
