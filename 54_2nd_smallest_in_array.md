## Problem Statement 

Second Smallest Element in an array using Python
 

Here, in this page we will discuss the program to find the second smallest element in an array using python programming language. We will discuss various method to find the second smallest element of the given array.

 
## Solution

```python
# Provide your solution here.
def function(lst):
    lst.sort()
    return lst[1]


listt = input("enter a list of values = ").split()
result = function(listt)
print(f"{result}")
