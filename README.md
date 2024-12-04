# README: JavaScript Tasks Solution

This document provides a brief explanation of the solutions implemented for the tasks involving **String Object**, **Math Object**, and **Array Object** in JavaScript.

---

## String Object Tasks

### 1.1 Palindrome Check
- **Description**: The script determines whether the entered string is a palindrome. It provides the user with the option to either consider or ignore case sensitivity.
- **Functionality**:
  - Prompts the user for a string.
  - Asks the user if case sensitivity should be considered.
  - Checks if the string reads the same forward and backward based on the user's preference.
  - Examples:
    - Case insensitive: `Radar`, `Noon`, and `MOOM` are palindromes.
    - Case sensitive: `raDaR` is not a palindrome.
    
---

### 1.2 Count 'e' Characters
- **Description**: The script accepts a string from the user and counts the number of occurrences of the character `e`.
- **Functionality**:
  - Prompts the user for a string input.
  - Iterates through the string to count the occurrences of `e`.
  - Outputs the total count to the user.

---

### 1.3 User Info Validation
- **Description**: This script reads user information (e.g., name, age, email) and validates the inputs.
- **Functionality**:
  - Prompts the user for their name, age, and email.
  - Validates:
    - Name: Non-empty and contains only letters.
    - Age: A valid number greater than 0.
    - Email: Matches a basic email format.
  - Displays a welcoming message with the validated information.

---

## Math Object Tasks

### 2.1 Circle Area Calculation
- **Description**: The script calculates the area of a circle based on the radius entered by the user.
- **Functionality**:
  - Prompts the user for the radius of a circle.
  - Uses the formula `Area = π * radius²` to calculate the area.
  - Alerts the user with the calculated area.

---

### 2.2 Square Root Calculation
- **Description**: The script calculates the square root of a value entered by the user.
- **Functionality**:
  - Prompts the user for a numeric input.
  - Computes the square root using `Math.sqrt`.
  - Alerts the user with the result.

---

## Array Object Tasks

### 3.1 Mathematical Operations on Array
- **Description**: This script performs mathematical operations (addition, multiplication, and division) on an array of three elements provided by the user.
- **Functionality**:
  - Prompts the user to input three numeric values.
  - Performs:
    - Addition of all elements.
    - Multiplication of all elements.
    - Division of the first element by the second and then the result by the third.
  - Outputs the results in a formatted way.

---

### 3.2 Array Sorting
- **Description**: The script sorts an array of five elements in both ascending and descending orders.
- **Functionality**:
  - Prompts the user to input five numeric values.
  - Sorts the array:
    - In ascending order using `Array.sort`.
    - In descending order using `Array.sort` with a compare function.
  - Displays both sorted arrays.

---

## Bonus Features
- Scripts include basic error handling (e.g., invalid inputs).
- User-friendly prompts and alerts for interaction.
- Modular and reusable functions for better code organization.

---

## How to Run
1. Copy the provided JavaScript code to a `.js` file or directly into the developer console of your browser.
2. Open an HTML file in a browser and include the script using the `<script>` tag.
3. Follow the prompts to execute each task.

Enjoy exploring the solutions! 😊
