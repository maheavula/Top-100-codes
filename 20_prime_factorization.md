## Problem Statement 

Find the Prime Factors of a Number in Python

Given an integer input as the number, the objective is to Find all the Prime Factors of a the given integer input number. Therefore, we’ll write a program to Find the Prime Factors of a Number in Python Language.

Example

Input : 10

Output : 2 5

## Solution

```python
# Provide your solution here.
def function(N):
    prime_factors = []
    for i in range(2,N):
        if N % i == 0 and is_prime(i):
            prime_factors.append(i)
    return ' '.join(map(str, prime_factors))

def is_prime(i):
    for j in range(2,i):
        if i % j == 0:
            return False
    return True

n = int(input("enter a number = "))
result = function(n)
print(result)

