## Problem Statement 

Check Whether or Not the Number is a Perfect Number in Python

Given an integer input as a number, the objective is to check whether or not a number is a Perfect Number in Python Language. Therefore, we write a program to Check Whether or Not the Number is a Perfect Number in Python Language.

Example

Input : 28

Divisors : [1, 2, 4, 7, 14]

Sum = 1 + 2 + 4 + 7 + 14 = 28

Output : It's a Perfect Number
## Solution

```python
# Provide your solution here.
from math import factorial

def function(N):
    lst = []
    for i in range(1,N):
        if N % i == 0:
            lst.append(i)
    s = sum(lst)
    return s == N

n = int(input("enter a number = "))
result = function(n)
if result:
    print(f"{n} is a perfect number")
else:
    print(f"{n} is not a perfect number")

