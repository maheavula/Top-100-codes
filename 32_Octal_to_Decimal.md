## Problem Statement 

Octal To Decimal Conversion

Here, in this page we will discuss the program for octal to decimal conversion in python . Octal numbers are also called numbers with base 8 and hold values from 0 – 7. Whereas in Decimal numbers are with base 10 is Standard number system for denoting integers and non-integers. 

## Solution

```python
# Provide your solution here.

def function(N):
    return int(N, 8)


n = input("enter a number = ")
result = function(n)
print(f"{result}")
