## Problem Statement 

GCD of Two numbers in Python

Here, in this section, we will discuss the GCD of two numbers in python. Basically, the GCD (Greatest Common Divisor) or HCF (highest common factor ) of two numbers is the largest positive integer that divides each of the integers where the user entered number should not be zero.

## Solution

```python
# Provide your solution here.
def function(N, M):
    gcd = 1
    for i in range(1, min(N, M)):
        if N % i == 0 and M % i == 0:
            gcd = i
    return gcd


n = int(input("enter a number = "))
m = int(input("enter a number = "))
result = function(n, m)
print(f"{result} is a GCD")
