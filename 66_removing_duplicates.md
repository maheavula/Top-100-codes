## Problem Statement 

Remove duplicate elements in Python
Here, in this section we will discuss the program to remove duplicate elements in python programming language. We will discuss two approaches to solve this program, by using extra space and without using extra space.
## Solution

```python
# Provide your solution here.

def function(lst):
    l1 = []

    for i in lst:
        if i not in l1:
            l1.append(i)
    return l1


if __name__ == "__main__":
    lst = list(map(int, input("enter list of numbers: ").split(",")))
    result = function(lst)
    print(result)
