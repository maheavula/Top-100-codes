## Problem Statement 

Count number of even and odd elements in Python
Here, in this page you will find the program to count number of even and odd elements in python programming language. We are given with an integer array and need to print the count of even elements and odd elements.
## Solution

```python
# Provide your solution here.
def function(lst):

    even_lst = []
    odd_lst = []

    for i in lst:
        if i % 2 == 0:
            even_lst.append(i)
        else:
            odd_lst.append(i)

    return even_lst, odd_lst

if __name__ == "__main__":
    lst = list(map(int, input("enter list of numbers: ").split(",")))
    result1, result2 = function(lst)
    print(result1, result2)

