## Problem Statement 

Check Whether a Number is a Prime or Not in Python

Given an integer input the objective is to write a program to Check Whether a Number is a Prime or Not in Python Language.

Example

Input : 11

Output : 11 is a Prime

## Solution

```python
# Provide your solution here.
def function(num):
    for i in range(2,num):
        if num % i != 0:
            return f"{num} is Prime number"
        else:
            return f"{num} is not prime number"


num = int(input("enter a number = "))
result = function(num)
print(result)
