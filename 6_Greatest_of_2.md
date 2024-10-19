## Problem Statement 

Find the Greatest of the Two Numbers

Given two integer inputs as number1 and number2, the objective is to find the largest among the two. Therefore we’ll write a code to Find the Greatest of the Two Numbers in Python Language.

Example

Input : 20 40

Output : 40

## Solution

```python
# Provide your solution here.
def function(c, d):
    return (f"{c} is greatest" if c>d else  f"{d} is greatest")

a = int(input("enter a number = "))
b = int(input("enter a number = "))
result = function(a,b)
print(result)
