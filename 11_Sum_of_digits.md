## Problem Statement 

Find the sum of the Digits of a Number in Python

Given an input the objective to find the Sum of Digits of a Number in Python. To do so we’ll first extract the last element of the number and then keep shortening the number itself.

Example

Input : number = 123

Output : 6

## Solution

```python
# Provide your solution here.
def function(num):
    return sum([int(i) for i in num])


num = input("enter a number = ")
result = function(num)
print(result)
