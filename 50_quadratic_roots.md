## Problem Statement 

Roots of a quadratic equation in Python

Here, in this page we will discuss the program to find the roots of a quadratic equation in python . In this python program, we will learn how to find the roots of a quadratic equation [ax2 + bx + c].

## Solution

```python
# Provide your solution here.
import math
def function(a,b,c):
    delta = b*b - 4*a*c
    if delta > 0:
        r1 = -b + math.sqrt(abs(delta)) / 2*a
        r2 = -b - math.sqrt(abs(dleta)) / 2*a
        return r1, r2
    elif delta == 0:
        r1 = -b / 2*a
        return r1
    elif delta < 0:
        return "roots are imaginary"


n = int(input("enter a number = "))
m = int(input("enter a number = "))
o = int(input("enter a number = "))
result = function(n,m,o)
print(f"{result}")
