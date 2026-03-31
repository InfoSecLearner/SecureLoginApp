# SecureLoginApp

A simple Java console application demonstrating basic secure coding practices such as input validation, safe error handling, and avoiding information disclosure.

## Features
- Input validation - Trims whitespace and restricts input to letters and numbers.
- Safe Error Handling - Shows a generic error message without exposing stack traces.
- Generic Authentication Error - Hides which credential failed during login.

## Not Secure By Design (Intentional for Learning)
- Hardcoded credentials (for demonstration only)
- No hashing or secure storage
- No rate limiting or lockout mechanism

## How to Run
1. Download the source file ([SecureLoginApp.java](SecureLoginApp.java)).
2. Install the Java Development Kit (JDK) if you don’t already have it.
3. Compile the program:
```Java
   javac SecureLoginApp.java
```
4. Run it:
```java
   java SecureLoginApp
```

## Learning Goals
- Understand basic secure coding principles
- Practice validating user input
- Learn safe error handling patterns

## Demo
<img width="317" height="124" alt="image" src="https://github.com/user-attachments/assets/2d002583-9d92-4c62-a92b-e54ef7c592f9" />

*Example of input validation and safe error messages.*
