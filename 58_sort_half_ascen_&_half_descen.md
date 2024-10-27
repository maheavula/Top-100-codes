## Problem Statement 

Sort First half in Ascending and Second half in descending order in Python
Here, in this page we will discuss the program to sort first half in ascending and second half in descending order in python programming language. We are given with an array and need to print the array in desired sorting way i.e, first half in increasing order and second half in descending order.
## Solution

```python
# Provide your solution here.

def function(lst):
    lst1 = sorted(lst)
    l = len(lst1)
    q = l/2
    for i in range(int(q+1)):
        if i < int(q):
            print(lst1[i], end=" ")
        else:
            return ' '.join(map(str,lst1[-1:int(-q-1):-1]))


n = list(map(int, input().split()))
result = function(n)
print(f"{result}")

