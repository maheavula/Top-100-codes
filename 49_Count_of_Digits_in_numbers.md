## Problem Statement 

Occurrence of a Digit in a given Number in Python
 
 
Here, in this page we will discuss the program to find the Occurrence of a Digit in a given Number in Python programming language. We will discuss different methods to solve this problem.

## Solution

```python
# Provide your solution here.
def function(st1, st2):
    return st1.count(st2)


n = input("enter a number = ")
m = input("enter a number to find = ")
result = function(n,m)
print(f"{result}")
