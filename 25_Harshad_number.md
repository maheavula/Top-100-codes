## Problem Statement 

Check Whether or Not a Number is a Harshad Number in Python

Given an integer input the objective is to check whether or not the given number is a Harshad Number or not. To do so we’ll check if the sum of the digits can perfectly divide the number or not. We’ll write a Program to Check Whether or Not a Number is a Harshad Number in Python Language.

Example

Input : 21

Output : Yes It's a Harshad Number

## Solution

```python
# Provide your solution here.
def function(N):
    add = 0
    for i in str(N):
        add += int(i)
    return N % add == 0


n = int(input("enter a number = "))
result = function(n)
if result:
    print(f"{n} is a Harshad Number.")
else:
    print(f"{n} is not a Harshad Number.")
