# Leap Year Checker in C

This project contains a simple C program that checks if a given year is a leap year or not.

## How the Program Works

The program uses basic conditions to check if the year entered by the user is a leap year. A year is a leap year if:
- It is divisible by 400, **or**
- It is divisible by 4 **but not** divisible by 100.

### Conditions:
1. If the year is divisible by 400, it is a leap year.
2. If the year is divisible by 100 but **not** divisible by 400, it is **not** a leap year.
3. If the year is divisible by 4 but **not** divisible by 100, it is a leap year.
4. Otherwise, it is **not** a leap year.

### Example:
- **Year 2000**: Leap year (divisible by 400)
- **Year 1900**: Not a leap year (divisible by 100 but not 400)
- **Year 2024**: Leap year (divisible by 4 and not by 100)
- **Year 2023**: Not a leap year (not divisible by 4)
