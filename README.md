# User Input Validation System

## Description
This project is a Java console application designed to collect and validate user information. It focuses on the implementation of **Exception Handling** using custom exception classes and centralized validation logic. The system ensures that all data entered by the user meets specific criteria before storing it in an `ArrayList`.

## Features
- **Custom Exceptions:** Implements `InvalidInputException` to handle specific validation failures.
- **Data Validation:** - **Name:** Ensures the field is not blank.
  - **Age:** Validates that input is a positive integer.
  - **Email:** Checks for the presence of `@` and specific domains (`.com`, `.edu`).
  - **Phone Number:** Ensures exactly 10 numeric digits.
- **Graceful Error Recovery:** Uses `try-catch` blocks within loops to re-prompt users until valid data is provided.

## How to Run
1. Ensure you have the [Java Development Kit (JDK)](https://www.oracle.com/java/technologies/downloads/) installed.
2. Clone this repository or download the source files.
3. Compile the classes:
   ```bash
   javac Main.java UserInputValidator.java InvalidInputException.java
