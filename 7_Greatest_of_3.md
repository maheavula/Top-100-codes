## Problem Statement 
Find the Greatest of the Three Numbers

Given three integer inputs the objective is to find the largest among them. Therefore we write a code to Find the Greatest of the Three Numbers in Python.

Example

Input : 20 30 10

Output : 30

## Solution

```python
# Provide your solution here.
def function(A, B, C):
    if (A > B and A > C):
        return f"{A} is Greatest"
    elif (B > C and B > A):
        return f"{B} is Greatest"
    else:
        return f"{C} is Greatest"

a = int(input("enter a number = "))
b = int(input("enter a number = "))
c = int(input("enter a number = "))
result = function(a,b,c)
print(result)
