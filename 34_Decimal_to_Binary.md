## Problem Statement 

Decimal to binary conversion in Python

Here, in this page we will discuss the program for Decimal to binary conversion in python. A decimal number is a standard representation of integers or non-integers, decimal numbers are also called as numbers with base 10. Whereas in binary number system numbers are with base 10 and shows representation by 0 and 1.

## Solution

```python
# Provide your solution here.

def function(N):
    return bin(N)[2:]


n = int(input("enter a number = "))
result = function(n)
print(f"{result}")
