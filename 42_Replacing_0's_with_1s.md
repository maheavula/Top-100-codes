## Problem Statement 

Replace All 0’s With 1 In A Given Integer using Python

Here we will discuss how to Replace All 0’s With 1 In A Given Integer using Python.

The concept is simple, find the digits of the integer. Compare each digit with 0 if the digit is equal to 0 then replace it with 1. Construct the new integer with the replaced digits.

## Solution

```python
# Provide your solution here.
def function(N):
    return str(N).replace('0','1')


n = int(input("enter a number = "))
result = function(n)
print(f"{result}")
