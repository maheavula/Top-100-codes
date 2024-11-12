## Problem Statement 

Counting Distinct Elements in Python
Here, in this page we will discuss the program for counting distinct elements in python programming language. We are given with an array and need to print the count of distinct element present in the given array.
## Solution

```python
# Provide your solution here.
def function(lst):

    new_lst = []
    for i in lst:
        if i in new_lst:
            pass
        else:
            new_lst.append(i)
    return len(new_lst)



if __name__ == "__main__":
    lst = list(map(int, input("enter list of numbers: ").split(",")))
    result = function(lst)
    print(result)
