# Basic Arithmetic Operations in C++

## Program Overview

This program is based on the fundamental concept of **arithmetic operations** in programming. It demonstrates how to use basic arithmetic operators in C++ to perform mathematical calculations such as addition, subtraction, multiplication, and division.

The inputs are taken from the user, and each result is calculated and printed. The program also highlights how data types affect the result and precision of arithmetic expressions.

---

## Working

The program performs the following steps:

1. Takes two numbers as input from the user (decimal values allowed)
2. Calculates:
   - Sum
   - Difference
   - Product
   - Quotient
3. Prints the result of each operation with appropriate labels

---

## Sample Output

Enter a Number: 75

Enter 2nd Number: 85

The Sum is: 160

The Product is: 6375

The Difference is: -10

The Division is: 0.882353


---

## Key Concepts Demonstrated

### 1. Arithmetic Operators
- Addition: `+`
- Subtraction: `-`
- Multiplication: `*`
- Division: `/`

These are used to perform standard mathematical operations between two numbers.

### 2. Data Types
- `float`: Used for variables `num1`, `num2`, and all result variables to **preserve decimal precision**.
- `int`: Initially used for storing some results (in the original version), which caused **loss of precision** due to implicit type conversion.

### 3. Input/Output
- `cin`: Accepts user input from the console
- `cout`: Prints output to the screen

### 4. Type Conversion (Implicit Casting)
- If `float` results are stored in `int` variables, C++ truncates the decimal part.  
- To avoid data loss, all results are stored in `float` variables.

### 5. Order of Execution
- Input is taken first
- Calculations are performed next
- Final results are displayed using `cout`

---

## Learning Outcomes

By working through this program, a beginner will learn:

- How to declare and use numeric data types like `float` in C++
- How to take user input using `cin` and print output using `cout`
- How arithmetic expressions are evaluated
- The importance of selecting the correct data type to preserve accuracy
- How implicit type conversion can affect the final result
