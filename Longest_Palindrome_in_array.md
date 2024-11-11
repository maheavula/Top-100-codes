## Problem Statement 

Longest Palindrome in an Array
Here, in this page we will discuss the program to find the longest palindrome in an array in python programming language, we will discuss two different methods to find the longest palindromic element in the given array.
## Solution

```python
# Provide your solution here.
from operator import index

lst = list(map(str, input("enter list of numbers = ").split()))

len_lst = []

for i in lst:
    if i == i[::-1]:
        len_lst.append(len(i))

ind = len_lst.index(max(len_lst))

print(lst[ind])

