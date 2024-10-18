## Problem Statement 

Find the Sum of The First N Natural Numbers in Python

Given an integer input the objective is to write a code to Find the Sum of First N Natural Numbers in C++. To do so we simply keep adding the value of the iter variable using a for loop.

Example

Input : num = 8

Output : 36

Where first 8 number is 1, 2, 3, 4, 5, 6, 7, 8

Sum of numbers = 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8 = 36

## Solution

```python
# Provide your solution here.
def function(num):
    return sum([i for i in range(num+1)])

result = function(8)
print(result)
