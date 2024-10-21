## Problem Statement 

Number of days in a given month of a given year in  Python

Here, in this page we will discuss the program to find the number of days in a given month of a given year in python . Number of days in any month of a year can vary specifically in February as the cycle of leap year repeats in every 4 years when the year is leap February gives the count to 29 days but the when the year is not leap it gives count to 28 days and so no of days in a year varies from 365 to 366.

## Solution

```python
# Provide your solution here.

def function(mon, year):
    if (year % 4 == 0 and year % 100 != 0) or year % 400 == 0:
        if mon == 2:
            return "29 days"
        elif mon in [1,3,5,7,8,10,12]:
            return "31 days"
        elif mon in [4,6,9,11]:
            return "30 days"
    else:
        if mon == 2:
            return "28 days"
        elif mon in [1,3,5,7,8,10,11,12]:
            return "31 days"
        elif mon in [4,6,9,11]:
            return "30 days"

n = int(input("enter a number = "))
m = int(input("enter a number = "))
result = function(n, m)
print(f"{result}")
