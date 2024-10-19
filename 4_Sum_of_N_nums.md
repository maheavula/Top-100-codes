## Problem Statement 

Find the Sum of N Natural Numbers in Python

Given an integer input number, the objective is to sum all the numbers that lay from 1 to the integer input number and print the sum. In order to do so we usually use iteration to sum all the numbers until the input variable number.

Example

Input : number = 5

Output : 15

Explanation : 1 + 2 + 3 + 4 + 5 = 15

## Solution

```python
# Provide your solution here.
def function(num):
    return sum([i for i in range(num+1)])

result = function(5)
print(result)
