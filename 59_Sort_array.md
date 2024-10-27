## Problem Statement 

Sort the Array in Python
Here, in this page we will discuss the program to sort elements of the given array in Python programming language. We will discuss the program to sort the given input array using inbuilt sort function.
## Solution

```python
# Provide your solution here.

def function(lst):
    n = len(lst)
    for i in range(n):
        for j in range(0,n-i-1):
            if lst[j] < lst[j+1]:
                lst[j], lst[j+1] = lst[j+1], lst[j]
    return lst

n = list(map(int, input().split()))
result = function(n)
print(f"{result}")

