## Problem Statement 

Repeating elements in an Array in Python
In this section we will discuss the program to find the repeating elements in an array in python programming language. We are given with an array and need to print the elements that occurs more than one times in the given input array.
## Solution

```python
# Provide your solution here.
def function(lst):
    qn_lst = []
    rep_strs = []

    for i in lst:
        if i in qn_lst:
            if i not in rep_strs:
                rep_strs.append(i)
        else:
            qn_lst.append(i)
    return ' '.join(map(str,sorted(rep_strs)))


if __name__ == "__main__":
    lst = list(map(int, input("enter list of numbers: ").split(",")))
    result = function(lst)
    print(result)

