## Problem Statement 

Factorial of a Number in Python

Here we will discuss how to find the Factorial of a Number in Python programming language.

Factorial of any number is the product of it and all the positive numbers below it for example factorial of 5 is 120

Factorial of n (n!) = 1 * 2 * 3 * 4....n

5! = 1 x 2 x 3 x 4 x 5 = 120 7! = 1 x 2 x 3 x 4 x 5 x 6 x 7 = 5040

## Solution

```python
# Provide your solution here.
def function(N):
    fact = 1
    for i in range(1,N+1):
        fact *= i
    return fact


n = int(input("enter a number = "))
result = function(n)
print(result)


# using recursion funciton
def factorial(N):
    fact = 1
    if N == 1:
        return N
    else:
        fact = N * factorial(N-1)

    return fact


n = int(input("enter a number = "))
result = factorial(n)
print(result)
