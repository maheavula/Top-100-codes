## Problem Statement 

HCF of Two Numbers

Here, in this section we will discuss how to find HCF of two numbers in python. HCF means (Highest Common Factor) also known as GCD (Greatest Common Divisor).

## Solution

```python
# Provide your solution here.

def function(N, M):
    hcf = 1
    for i in range(1, min(N, M)):
        if N % i == 0 and M % i == 0:
            hcf = i
    return hcf


n = int(input("enter a number = "))
m = int(input("enter a number = "))
result = function(n, m)
print(f"{result} is a HCF")
