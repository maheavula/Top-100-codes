## Problem Statement 

Non-repeating elements in an array in python
Here, in this page we will discuss the program to print the non-repeating elements in python programming language. We are given with an integer array and need to print those elements which occurs only one time.
## Solution

```python
# Provide your solution here.
def function(lst):
    dit = {}
    for i in lst:
        if i in dit:
            dit[i] += 1
        else:
            dit[i] = 1

    for i, j in dit.items():
        if j > 1:
            pass
        else:
            print(f"{i}", end=" ")


if __name__ == "__main__":
    lst = list(map(int, input("enter list of numbers: ").split(",")))
    result = function(lst)
    print(result)

