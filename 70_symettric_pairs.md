## Problem Statement 

Symmetric pairs in array in Python
In this page you will find the program to print all symmetric pairs in an array in python programming language. We are given with an array and need to print the all symmetric pairs present in the given array.
## Solution

```python
# Provide your solution here.

def function():
    lst = [(10,20), (30,40), (50,60), (20,10), (40,30), (90, 100), (1, 9), (100, 90)]
    l1 = []
    for i in lst:
        if sorted(i) not in l1:
            l1.append(sorted(i))
        else:
            print(sorted(i))

if __name__ == "__main__":
    function()
