# Unit Testing Assignment – Gradle Project

## Group Members
- Ron Briskin  
- Daniel Dzyuba (in miluim)



## Functions and Responsibilities

This project includes multiple Java methods with corresponding unit tests written in JUnit.  
Since Daniel is currently serving in the reserves, I (Ron) handled the code implementation and testing.

The following methods were tested:
- `add(int a, int b)` – adds two numbers
- `isPrime(int n)` – checks if a number is prime
- `reverse(String s)` – reverses a string
- `factorial(int n)` – calculates the factorial of a number
- `isPalindrome(String s)` – checks if a string is a palindrome
- `fibonacciUpTo(int n)` – returns a list of Fibonacci numbers up to `n`

Each method has at least one corresponding test method in the `AppTest` class using JUnit’s `assert` statements.

### What the user needs to do:
To test the code:
```bash
./gradlew test
