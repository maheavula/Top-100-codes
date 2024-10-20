## Problem Statement 

LCM of two numbers in Python
 

Here, in this section we will discuss the LCM of two numbers in python.

In this Python Program find the LCM of Two Numbers which numbers are entered by the user. Basically the LCM of two numbers is the smallest number which can divide the both numbers equally. This is also called Least Common Divisor or LCD.

## Solution

```python
# Provide your solution here.

def function(N, M):
    hcf = 1
    for i in range(1, max(N, M)):
        if N % i == 0 and M % i == 0:
            hcf = i
    lcm = (N * M) // hcf
    return lcm


n = int(input("enter a number = "))
m = int(input("enter a number = "))
result = function(n, m)
print(f"{result} is a HCF")
