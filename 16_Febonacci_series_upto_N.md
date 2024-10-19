## Problem Statement 

Find the Fibonacci Series up to Nth Term in Python

Given an integer as an input, the objective is to find the Fibonacci series until the number input as the Nth term. Therefore, we write a program to Find the Fibonacci Series up to Nth Term in Python Language.

Example

Input : 4

Output : 0 1 1 2

## Solution

```python
# Provide your solution here.
def function(N):
    a = 0
    b = 1
    print(a,b, end=" ")
    for i in range(2,N):
        c = a + b
        a = b
        b = c
        print(c, end=" ")
    print()


n = int(input("enter a number = "))
result = function(n)
print(result)
