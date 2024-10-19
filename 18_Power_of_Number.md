## Problem Statement 

Find the Power of a Number in Python Language

Given two integer input numbers, the objective is to find the power of the number raise to the power variable. Therefore, we’ll write a code to Find the Power of a Number in Python Language.

Example

Input : 2 3

Output : 8

## Solution

```python
# Provide your solution here.
def function(N, P):
    return N**P


n = int(input("enter a number = "))
p = int(input("enter a number = "))
result = (function(n, p))
print(result)
