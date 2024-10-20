## Problem Statement 

Octal To Binary Conversion in Python

Here, in this page we will discuss the program for octal to binary conversion in Python . Numbers with base 8 are called octal numbers and uses digits from 0-7 for representation of octal number. Where as numbers with base 2 are called binary numbers  and it uses 0 and 1 for representation of binary numbers.

## Solution

```python
# Provide your solution here.
def function(N):
    octal = int(N,8)
    return bin(octal)[2:]


n = input("enter a number = ")
result = function(n)
print(f"{result}")
