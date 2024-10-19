## Problem Statement 

Find the Factors of a Number in Python

Given an integer Number as input, the objective is to search for all the factors of the Given integer input. Therefore, we write a program to Find the Factors of a Number in Python Language.

Example

Input : 10

Output : 2 5

## Solution

```python
# Provide your solution here.
def function(N):
    lst = []
    for i in range(2, N):
        if N % i == 0:
            lst.append(i)

    return ' '.join(map(str, lst))

n = int(input("enter a number = "))
result = function(n)
print(result)

