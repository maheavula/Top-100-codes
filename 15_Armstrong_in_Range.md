## Problem Statement 

Find the Armstrong Number in a given Range in Python

Given two integers high and low for limits as inputs, the objective is to write a code to Find the Armstrong Numbers in a given Interval in C++. 

For Instance,

Input : 150 160

Output : 153

## Solution

```python
# Provide your solution here.
def function():
    s = 0
    lst = []
    for i in range(150,1635):
        for j in str(i):
            s += int(j)**len(str(i))
        if int(i) == int(s):
            lst.append(i)
        s = 0
    return lst


#num = input("enter a number = ")
result = function()
print(result)
