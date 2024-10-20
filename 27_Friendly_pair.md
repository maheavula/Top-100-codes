## Problem Statement 

Check Whether or Not the Two Numbers  are Friendly Pairs in Python

Given two integer numbers as the input, the objective is to check whether or not the two numbers are Friendly pairs of each other. Therefore, we’ll write a Program to Check Whether or Not the Two Numbers are Friendly Pairs in Python.

Example

Input : 6 28

Output : Yes, they are a friendly pair

## Solution

```python
# Provide your solution here.

def function(N, M):
    nl = []
    ml = []
    for i in range(1,N):
        if N % i == 0:
            nl.append(i)
    snl = sum(nl)
    for j in range(1, M):
        if M % j == 0:
            ml.append(j)
    sml = sum(ml)
    rn = snl / N
    rm = sml / M

    return int(rn) == int(rm)


n = int(input("enter a number = "))
m = int(input("enter a number = "))
result = function(n, m)
if result:
    print(f"{n} is a Friendly pair")
else:
    print(f"{n} is not a Friendly pair.")

