## Problem Statement 

Reverse an Array using Python

Here, in this page we will discuss the program to reverse an array using python programming language. We will discuss different approaches to reverse the array in this page and compare the complexity of different approaches.

## Solution

```python
# Provide your solution here.
def function(lst):
    return lst[::-1]


listt = input("enter a list of values = ").split()
result = function(listt)
print(f"{result}")
