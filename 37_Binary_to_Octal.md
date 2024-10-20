## Problem Statement 

Binary to Octal Conversion in Python

Here, in this section we will discuss the binary to octal conversion in Python.Binary numbers are also known as bits that represent 0 means FALSE and 1 means TRUE, but usually binary numbers are with base 2 and can represent any number in form of 0 and 1. Whereas Octal numbers expressed with base 8 and can represent any number with 0 to 7.

## Solution

```python
# Provide your solution here.
def function(N):
    binary = int(N,2)
    return oct(binary)[2:]


n = input("enter a number = ")
result = function(n)
print(f"{result}")
