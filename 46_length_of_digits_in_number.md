## Problem Statement 

Number of digits in an integer in Python

Number of Digits in an integer in python program to find the length of the Integer entered by the user. The number of digits present in the Integer is the length of the Integer. Every Character or Integer or any other variable or constant either given by the user or predefined has some length.

## Solution

```python
# Provide your solution here.

def function(N):
    return len(str(N))

n = int(input("enter a number = "))
result = function(n)
print(f"{result}")
