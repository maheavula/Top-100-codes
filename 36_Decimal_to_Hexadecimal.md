## Problem Statement 

Decimal to Hexadecimal Conversion in Python

On this page we will learn the concept of decimal to hexadecimal conversion in Python.

We will also learn to Decimal to Hexadecimal Conversion in Python Programing language.

## Solution

```python
# Provide your solution here.
def function(N):
    return hex(N)[2:]


n = int(input("enter a number = "))
result = function(n)
print(f"{result}")
