## Problem Statement 

Frequency of Elements in an Array in Python
Here, in this page we will discuss the program to count the frequency of elements in an array in python programming language. We are given with an array and need to print each element along its frequency.
## Solution

```python
# Provide your solution here.

def function(lst):
    dit = {}
    for i in lst:
        if i in dit.keys():
            dit[i] = dit[i] + 1
        else:
            dit[i] = 1
    for i,j in dit.items():
        print(f"{i}:{j}")

if __name__ == "__main__":
    l = list(map(int, input().split()))
    result = function(l)
    print(result)
