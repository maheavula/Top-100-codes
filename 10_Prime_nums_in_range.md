## Problem Statement 

Find the Prime Numbers in a Given Range in Python

Given two integer as Limits, low and high, the objective is to write a code to in Python Find Prime Numbers in a Given Range in Python Language. To do so we’ll use nested loops to check for the Prime while Iterating through the range.

Example

Input : low = 2 , high = 10

Output : 2 3 5 7

## Solution

```python
# Provide your solution here.
def function(l, h):
    s = ""
    for i in range(l,h+1):
        for j in range(2,i):
            if i % j == 0:
                break
        else:
            s += str(i) + " "
    return s


low = int(input("enter a number = "))
high = int(input("enter a number = "))
result = function(low, high)
print(result)
