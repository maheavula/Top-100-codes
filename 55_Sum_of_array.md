## Problem Statement 

Sum of Elements in an array using Python

Here, in this page we will discuss the program to find the sum of elements in an array using Python programming language. We are given with an array and need to print the sum of its element. In this page we will discuss different ways to find the sum.

## Solution

```python
# Provide your solution here.
def function(lst):
    summ = 0
    for i in lst:
        summ += int(i)
    return summ


listt = input("enter a list of values = ").split()
result = function(listt)
print(f"{result}")
