## Problem Statement 

Sorting elements of an Array by Frequency in Python
Here, in this article we will discuss the program for sorting elements of an array by frequency in python programming language. We will discuss various algorithms for sorting.
## Solution

```python
# Provide your solution here.

def function(lst):
    return sorted(lst, key=lst.count, reverse=True)

if __name__ == "__main__":
    l = list(map(int, input().split()))
    result = function(l)
    print(result)
