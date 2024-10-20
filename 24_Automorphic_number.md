## Problem Statement 

Check Whether or Not the Number is an Automorphic Number in Python

Given an integer input for a number, the objective is to check whether or not the number is Automorphic or not. Therefore we’ll write a program to Check Whether or Not the Number is an Automorphic Number in Python Language.

Example

Input : 5

Output : It's an Automorphic Number.

## Solution

```python
# Provide your solution here.

def function(N):
    l = len(str(N))
    sq = str(N**N)
    return int(sq[-l:]) == N

n = int(input("enter a number = "))
result = function(n)
if result:
    print(f"{n} is a Automorphic Number.")
else:
    print(f"{n} is not a Automorphic Number.")
