## Problem Statement 

Check for Perfect Square in Python

Here on this page, we will learn how to Check for Perfect Square in Python programming language. We are given an integer number and need to print “True” if it is, otherwise “False”.

## Solution

```python
# Provide your solution here.
import math

def function(N):
    if N >= 0:
        S = int(math.sqrt(N))
        return (S * S) == N
    return False

n = int(input("enter a number = "))
result = function(n)
if result:
    print(f"{n} is a perfect Square")
else:
    print(f"{n} is not a perfect Square")
