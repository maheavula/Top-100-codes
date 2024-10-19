## Problem Statement 

Find the Reverse of a Number in Python

Given an integer input the objective is to reverse the given integer number using loops and slicing. Therefore, we’ll write a program to Find the Reverse of a Number in Python Language.

Example

Input : 123

Output : 321

## Solution

```python
# Provide your solution here.
def function(num):
    n_num = num
    r_num = ""
    for i in range(len(str(num))):
        q = n_num % 10
        n_num = n_num // 10
        r_num += str(q)
    return r_num

num = int(input("enter a number = "))
result = function(num)
print(result)
