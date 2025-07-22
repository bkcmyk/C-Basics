This C++ program performs basic arithmetic operations (addition, subtraction, multiplication, and division) on two user-input floating-point numbers. It calculates the:
Sum
Difference
Product
Quotient
and then displays each result with appropriate labels.

****

This program is based on the fundamental concept of arithmetic operations in programming. In any programming language, arithmetic operators are used to perform basic mathematical calculations. The most common operators include:
+ → Addition
- → Subtraction
* → Multiplication
/ → Division

 Key Concepts:
1. Data Types:
float: Used for storing decimal (floating-point) numbers.
int: Used for whole numbers (integers).
In this program, num1 and num2 are declared as float to allow decimal inputs. However, some results are stored in int, which may lose decimal precision.

2.Input/Output:
cin is used to take input from the user.
cout is used to display the results on the screen.

3.Type Conversion (Implicit Casting):
When performing operations between float and storing them in int variables (like sum, diff, and product), C++ automatically converts (truncates) the result to an integer. This may lead to a loss of decimal values.
Division (/) is stored in a float to preserve decimal accuracy.

4.Order of Execution:
The program executes from top to bottom, first taking input, then performing operations, and finally displaying the results.


 Purpose:
This type of program helps beginners understand:
How to take input and give output in C++
How to perform and store arithmetic calculations
The behavior of data types in arithmetic expressions
