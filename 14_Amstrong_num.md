## Problem Statement 

Check Whether a Given Number is an Armstrong Number or Not in Python

For a given integer the objective is to check whether or not the given integer is an Armstrong number or not. The Armstrong number is briefly defined in the section below.

Example

Input : 371

Output : It's an Armstrong Number

## Solution

```python
# Provide your solution here.
def function(num):
    s = 0
    for i in num:
        s += int(i)**len(num)
    return ("It is a Amstrong" if int(num) == s else "Not a amstrong")


num = input("enter a number = ")
result = function(num)
print(result)
