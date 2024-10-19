## Problem Statement 

Check Whether or Not the Number is a Palindrome in Python

Given an integer number as an input, the objective is to check Whether or not the number is a palindrome. Therefore, we write a code to Check Whether or Not the Number is a Palindrome in Python Language.

Example

Input : 1221

Output : Palindrome

## Solution

```python
# Provide your solution here.
def function(num):
    n_num = num
    r_num = ""
    for i in range(len(str(num))):
        q = n_num % 10
        n_num = n_num // 10
        r_num += str(q)
    return ("palindrome" if int(r_num) == int(num) else "not palindrome")

num = int(input("enter a number = "))
result = function(num)
print(result)
