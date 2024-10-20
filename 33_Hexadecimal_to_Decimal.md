## Problem Statement 

Hexadecimal to Decimal Conversion

On this page we will learn how to create a python program for Hexadecimal to Decimal Conversion.

Hexadecimal has numbers in the range of [0, 15] and to achieve so it also uses some characters of alphabets.

## Solution

```python
# Provide your solution here.

def function(N):
    return int(N, 16)


n = input("enter a number = ")
result = function(n)
print(f"{result}")
