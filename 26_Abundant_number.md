## Problem Statement 

Check Whether or Not the Number is an Abundant Number in Python

Given an integer input as the number, the objective is to check whether or the given integer number is an Abundant Number or not. Therefore, we’ll write a program to Check Whether or Not the Number is an Abundant Number in Python Language.

Example

Input : 21

Output : It's not an Abundant Number. 

## Solution

```python
# Provide your solution here.

def function(N):
    summ = 0
    for i in range(1, N):
        if N % i == 0:
            summ += i
    return N < summ


n = int(input("enter a number = "))
result = function(n)
if result:
    print(f"{n} is a Abundant Number.")
else:
    print(f"{n} is not a Abundant Number.")

