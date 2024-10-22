## Problem Statement 

Largest Element in an array using python

Here, in this page we will discuss the program to find the largest element in an array using python we are given with an array elements and we need to print the largest among the given elements. We discuss different methods to find the largest element using python programing language.

## Solution

```python
# Provide your solution here.
def function(lst):
    maxx = lst[0]
    for i in range(len(lst)):
        if lst[i] > maxx:
            maxx = lst[i]
    return maxx


listt = input("enter a list of values = ").split()
result = function(listt)
print(f"{result}")
