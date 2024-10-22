## Problem Statement 

Find smallest element in an array using Python

In this section we will learn how to find smallest element in an array using python programming language which is the scripting language. If we want to find smallest element from the array enter by the user so we have to compare one element to other until we get the desired element and print it.

## Solution

```python
# Provide your solution here.
def function(lst):
    minn = lst[0]
    for i in range(len(lst)):
        if lst[i] < minn:
            minn = lst[i]
    return minn


listt = input("enter a list of values = ").split()
result = function(listt)
print(f"{result}")
