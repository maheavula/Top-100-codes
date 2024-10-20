## Problem Statement 

Quadrant in which the given co-ordinate lie in Python

Here, in this page we will discuss the program to find the quadrant in which the given co-ordinate lie in python . From the origin at x = 0 and y = 0, a pointy can move in four different directions. There are 4 coordinates available when we think in 2-Dimension. These 2-dimensions are at X-axis and Y-axis. Now based on their positive or negative nature this axis shows 4 different quadrants. This 4-Quadrants are different and are as follows.

## Solution

```python
# Provide your solution here.

def function(N,M):
    if N > 0 and M > 0:
        return f"{n} and {M} lies at first quadrant"
    elif N < 0 and M > 0:
        return f"{n} and {M} lies at second quadrant"
    elif N > 0 and M < 0:
        return f"{n} and {M} lies at Fourth quadrant"
    elif N < 0 and M < 0:
        return f"{n} and {M} lies at Third quadrant"
    elif N == 0 and M == 0:
        return f"{n} and {M} lies at origin"
    elif N == 0 and M != 0:
        return f"{N} lies at X-axis"
    elif M == 0 and N != 0:
        return f"{M} lies at Y-axis"

n = int(input("enter a number = "))
m = int(input("enter a number = "))
result = function(n,m)
print(f"{result}")
