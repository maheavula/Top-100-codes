## Problem Statement 

Find Prime number between 1 to 100

Here, in this page we will discuss program to find Prime number between 1 to100 in python .A prime number is an positive integer that has no divisors  except one and itself or can only be exactly divided by the integers 1 and itself without leaving a remainder.

## Solution

```python
# Provide your solution here.
import math
def function(N):
    prim_lst = []
    for i in range(2,N):
        is_prime = True
        for j in range(2,i):
            if i % j == 0:
                is_prime = False
                break
        if is_prime:
            prim_lst.append(i)
    return ','.join(map(str, prim_lst))

n = int(input("enter a number = "))
result = function(n)
print(f"{result}")
