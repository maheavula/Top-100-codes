## Problem Statement 

Minimum scalar product of  two vectors in Python
Here, in this page you will find the program to find the minimum scalar product of two vectors in Python Programming Language. We will discuss different methods to find the product of given two vectors.
## Solution

```python
# Provide your solution here.

def function(lst1, lst2):

    l1 = sorted(lst1)
    l2 = sorted(lst2, reverse=True)
    prod = 0
    for i in range(0, len(l1)):
        prod += l1[i] * l2[i]
    return prod


if __name__ == "__main__":
    lst1 = list(map(int, input("enter list of numbers: ").split(",")))
    lst2 = list(map(int, input("enter list of numbers: ").split(",")))
    result = function(lst1,lst2)
    print(result)
