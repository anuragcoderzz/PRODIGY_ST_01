# Test Cases for Calculator Application

## Overview
These test cases are created for a calculator application to verify its basic operations: addition, subtraction, multiplication, and division. The test cases cover both positive and negative scenarios, including valid inputs, invalid inputs, and edge cases like division by zero.

## Test Case 1: Addition with Valid Positive Numbers
- **Test Case ID**: TC_01  
- **Test Description**: Verify that the calculator correctly adds two positive numbers.  
- **Preconditions**: Calculator app is open and set to perform addition.  
- **Test Steps**:  
  1. Enter the first number as 5.  
  2. Enter the second number as 3.  
  3. Press the "+" button.  
  4. Press the "=" button.  
- **Expected Results**: The result displayed is 8.

## Test Case 2: Subtraction with Valid Numbers
- **Test Case ID**: TC_02  
- **Test Description**: Verify that the calculator correctly subtracts one number from another.  
- **Preconditions**: Calculator app is open and set to perform subtraction.  
- **Test Steps**:  
  1. Enter the first number as 10.  
  2. Enter the second number as 4.  
  3. Press the "-" button.  
  4. Press the "=" button.  
- **Expected Results**: The result displayed is 6.

## Test Case 3: Multiplication with Decimal Numbers
- **Test Case ID**: TC_03  
- **Test Description**: Verify that the calculator correctly multiplies two decimal numbers.  
- **Preconditions**: Calculator app is open and set to perform multiplication.  
- **Test Steps**:  
  1. Enter the first number as 2.5.  
  2. Enter the second number as 3.2.  
  3. Press the "×" button.  
  4. Press the "=" button.  
- **Expected Results**: The result displayed is 8.0.

## Test Case 4: Division with Valid Numbers
- **Test Case ID**: TC_04  
- **Test Description**: Verify that the calculator correctly divides one number by another.  
- **Preconditions**: Calculator app is open and set to perform division.  
- **Test Steps**:  
  1. Enter the first number as 15.  
  2. Enter the second number as 3.  
  3. Press the "÷" button.  
  4. Press the "=" button.  
- **Expected Results**: The result displayed is 5.

## Test Case 5: Division by Zero
- **Test Case ID**: TC_05  
- **Test Description**: Verify that the calculator handles division by zero appropriately.  
- **Preconditions**: Calculator app is open and set to perform division.  
- **Test Steps**:  
  1. Enter the first number as 10.  
  2. Enter the second number as 0.  
  3. Press the "÷" button.  
  4. Press the "=" button.  
- **Expected Results**: Error message displayed: "Cannot divide by zero" or "Undefined".

## Test Case 6: Invalid Input with Letters
- **Test Case ID**: TC_06  
- **Test Description**: Verify that the calculator rejects invalid inputs like letters.  
- **Preconditions**: Calculator app is open.  
- **Test Steps**:  
  1. Enter the first input as "abc".  
  2. Enter the second number as 5.  
  3. Press the "+" button.  
  4. Press the "=" button.  
- **Expected Results**: Error message displayed: "Invalid input. Please enter a number".