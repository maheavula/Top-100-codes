## Problem Statement 

Decimal to octal conversion

Here, in this section we will discuss the program for decimal to octal conversion in python. Decimal numbers are the standard representation for representing integer or non-integer values. Decimal numbers are with base 10 and can represent numbers from 0-9. Whereas in Octal representation of numbers, numbers from 0-7 are represented as octal numbers are with base 8.

## Solution

```python
# Provide your solution here.
def function(N):
    return oct(N)[2:]


n = int(input("enter a number = "))
result = function(n)
print(f"{result}")
