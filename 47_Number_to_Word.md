## Problem Statement 

Converting digit/number to words in Python

Here, in this page we will discuss the program for Digit/number to words in Python .The conversion of numbers in words is just a conversion of numeric values to the English format of reading numbers. This code supports the conversion of numbers from 0 – 9999 in English format.

## Solution

```python
# Provide your solution here.
import num2words

def function(N):
    return num2words.num2words(N), num2words

n = int(input("enter a number = "))
result = function(n)
print(f"{result}")
