## Problem Statement 

Find the Sum of the Numbers in a Given Range

Given two integer inputs as the range [ low , high ], the objective is to find the sum of the numbers that lay in the intervals given by the integer inputs. Therefore we’ll write a code to Find the Sum of the Numbers in a Given Range in Python Language.

Example

Input : 2 5

Output : 14

## Solution

```python
# Provide your solution here.
def function(start, end):
    return sum([i for i in range(start,end+1)])

s = int(input("enter a number = "))
e = int(input("enter a number = "))
result = function(s,e)
print(result)
