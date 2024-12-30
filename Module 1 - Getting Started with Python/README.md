# Assignment and Case Study on If-Else, Conditionals, and Loops

## Overview
This repository contains a series of **Python programs** designed to demonstrate the use of basic programming concepts such as **if-else statements**, **conditional statements**, and **loops**. The assignment and case study cover practical use cases where these concepts are applied to solve problems effectively.

## Objective
The primary objective of this case study is to:
- Implement decision-making logic using **if-else statements**.
- Utilize **conditional statements** to evaluate and choose between different paths in the program.
- Work with **loops (for and while)** to repeat operations efficiently.

## Topics Covered
- **If-Else Statements**: 
    - Conditional checking and branching.
    - Comparing numbers, strings, and other data types.
    - Handling edge cases and unexpected input.
  
- **Conditional Statements**:
    - Using logical operators (e.g., `and`, `or`, `not`).
    - Nested conditions for complex decision-making processes.

- **Loops**:
    - **For Loops**: Iterating over ranges, lists, and other data structures.
    - **While Loops**: Repeating actions until a condition is met.
    - Using loops to simplify repetitive tasks.

## Case Study: Example Scenarios

### 1. **Find the Greatest Number**
   - Implemented an `if-else` condition to compare three user inputs and print the greatest number among them.
   - Example:
     ```python
     a = int(input("Enter first number: "))
     b = int(input("Enter second number: "))
     c = int(input("Enter third number: "))

     if a >= b and a >= c:
         print(f"The greatest number is {a}")
     elif b >= a and b >= c:
         print(f"The greatest number is {b}")
     else:
         print(f"The greatest number is {c}")
     ```

### 2. **Loop through Numbers (1 to 10)**
   - Demonstrated the use of **while loop** to print numbers from 1 to 10.
   - Example:
     ```python
     i = 1
     while i <= 10:
         print(i)
         i += 1
     ```

### 3. **Extract Even Numbers from List Using While Loop**
   - Utilized a `while` loop to fetch even numbers from a list and print them.
   - Example:
     ```python
     numbers = [10, 23, 4, 26, 4, 75, 24, 54]
     i = 0
     while i < len(numbers):
         if numbers[i] % 2 == 0:
             print(numbers[i])
         i += 1
     ```

### 4. **Prime Number Checker**
   - Used a `for` loop to check if a number is prime or not, with conditional checks.
   - Example:
     ```python
     def is_prime(num):
         if num <= 1:
             return False
         for i in range(2, num):
             if num % i == 0:
                 return False
         return True
     
     number = int(input("Enter a number: "))
     if is_prime(number):
         print(f"{number} is a prime number")
     else:
         print(f"{number} is not a prime number")
     ```

## Assignment Details
In this assignment, I applied these concepts to solve real-world problems:
- **If-else** was used to make decisions based on user input or conditions.
- **Loops** were used to iterate over data and perform repetitive tasks, making the program efficient and concise.

## Challenges and Learning Points
- **Edge Cases Handling**: Ensuring that the program can handle unexpected input, such as negative numbers or zero.
- **Complex Logic**: Combining multiple **if-else** conditions and loops to handle complex scenarios like prime number checking, list filtering, etc.
- **Code Optimization**: Learning how to write efficient code using loops instead of repeating logic.

## Conclusion
This assignment has helped me understand the practical use of **if-else**, **conditional statements**, and **loops** in programming. These concepts are fundamental to building logical and efficient programs that can handle a variety of tasks.

