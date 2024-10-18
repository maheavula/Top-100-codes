## Problem

Check Whether a Number is Even or Odd in Python.

Given an integer input num, the objective is to write a code to Check Whether a Number is Even or Odd in Python. To do so we check if the number is divisible by 2 or not, it’s Even if it’s divisible otherwise Odd.

Example 

Input : num = 3

Output : Odd 

## Solution
````python
num = int(input("num = "))
print(("Even" if (num % 2 == 0) else "Odd"))
