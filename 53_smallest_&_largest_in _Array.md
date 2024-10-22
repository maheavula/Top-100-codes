## Problem Statement 

Smallest and Largest Element in an array using Python
 
Here, in this page we will discuss the program to find the smallest and largest element in an array using python programming language. We will discuss different algorithms to find the smallest and largest element of the given input array.

## Solution

```python
# Provide your solution here.
def function(lst):
    minn = lst[0]
    maxx = lst[0]
    for i in range(len(lst)):
        if lst[i] < minn:
            minn = lst[i]
        else:
            maxx = lst[i]
    return minn, maxx


listt = input("enter a list of values = ").split()
result = function(listt)
print(f"{result}")
