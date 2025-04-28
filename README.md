# KDG Calculator

A simple calculator package that provides basic arithmetic operations.

## Features

- Addition
- Subtraction
- Multiplication
- Division (with zero division checking)

## Installation

You can install KDG Calculator using pip:

```bash
pip install kdg-calculator
```

Or clone this repository:

```bash
git clone https://github.com/krishnendudg/kdg-calculator.git
cd kdg-calculator
```

## Usage

```python
from kdg_calculator import Calculator

# Create a calculator instance
calc = Calculator()

# Addition
result = calc.add(5, 3)  # Returns 8

# Subtraction
result = calc.subtract(10, 4)  # Returns 6

# Multiplication
result = calc.multiply(2, 6)  # Returns 12

# Division
result = calc.divide(8, 2)  # Returns 4
# Note: Division by zero will raise ZeroDivisionError
```

## API Reference

### `Calculator` class

#### Methods

- `add(a, b)`: Returns the sum of two numbers
- `subtract(a, b)`: Returns the difference between two numbers
- `multiply(a, b)`: Returns the product of two numbers
- `divide(a, b)`: Returns the quotient of two numbers (raises `ZeroDivisionError` if b is 0)

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
