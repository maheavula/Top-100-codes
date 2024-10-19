## Problem Statement 

Check if a Year is a Leap Year or Not in Python

Given an integer input year, the objective of the code is to Check if a Year is a Leap Year or Not in Python Language. To do so  we’ll check if the year input satisfies either of the two conditions of leap year.

Example

Input : 2020

Output : It's a Leap Year.

## Solution

```python
# Provide your solution here.
def function(year):
    if (year % 4 == 0 and year % 100 != 0) or year % 400 == 0:
        return f"{year} is a leap year"
    else:
        return f"{year} is not a leap year"

year = int(input("enter a number = "))
result = function(year)
print(result)
