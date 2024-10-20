## Problem Statement 

Check Whether or Not the Number is a Strong Number in Python

Given an integer input the objective is to check whether or not the given integer input is a Strong Number based on whether is satisfies the condition or not. Therefore, we’ll write a program to Check Whether or Not the Number is a Strong Number in Python Language.

Example

Input : 145

Output : It's a Strong Number

## Solution

```python
# Provide your solution here.
from math import factorial

def function(N):
    s = 0
    for i in str(N):
        s += factorial(int(i))
    return s == N

n = int(input("enter a number = "))
result = function(n)
if result:
    print(f"{n} is a strong number")
else:
    print(f"{n} is not a strong number")

