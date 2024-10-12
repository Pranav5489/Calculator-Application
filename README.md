# Calculator Application

## Description
A basic calculator application created using C. This program allows users to perform arithmetic operations such as addition, subtraction, multiplication, and division.

## Features
- Simple user interface for performing basic arithmetic operations.
- Handles division by zero errors.
- Strengthened understanding of algorithms and logic building.

## Installation

To compile and run the calculator application, you need a C compiler installed on your machine (like GCC).

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/calculator-application.git
    cd calculator-application
    ```

2. Compile the program:
    ```bash
    gcc -o calculator calculator.c
    ```

3. Run the program:
    ```bash
    ./calculator
    ```

## Usage

1. Select an operation by entering the corresponding number.
2. Follow the prompts to enter the numbers for the operation.
3. The result will be displayed on the console.
4. Type '5' to exit the application.

## Code Example

Here’s a snippet of the code used to create the calculator:

```c
void add() {
    float a, b;
    printf("Enter two numbers: ");
    scanf("%f %f", &a, &b);
    printf("Result: %.2f\n", a + b);
}
