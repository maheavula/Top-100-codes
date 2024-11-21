## Problem Statement 

Maximum Scalar Product of two Vectors in Python
Here, in this page we will discuss the program to find the maximum scalar product of two vectors in python programming language. Scalar product is also known as dot product. We are given with two vectors and need to print the maximum dot product obtained.
## Solution

```python
# Provide your solution here.
def function(lst1, lst2):

    l1 = sorted(lst1)
    l2 = sorted(lst2)
    prod = 0
    for i in range(0, len(l1)):
        prod += l1[i] * l2[i]
    return prod


if __name__ == "__main__":
    lst1 = list(map(int, input("enter list of numbers: ").split(",")))
    lst2 = list(map(int, input("enter list of numbers: ").split(",")))
    result = function(lst1,lst2)
    print(result)

