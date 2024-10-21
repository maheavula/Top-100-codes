## Problem Statement 

How to find area of circle using python ?

Here, in this page we will discuss the progrm to find area of circle using python .Area of circle is the number of square units inside the circle , can be calculated using the radius and diameter.The formula for evaluating the area of circle is

Area of circle using radius=   Pi*r*r    ( r is the radius of circle)## Solution

```python
# Provide your solution here.
import math
def function(R):
    area = math.pi * R*R
    return f"Area of circle is {area:.3f}"

n = int(input("enter a number = "))
result = function(n)
print(f"{result}")
