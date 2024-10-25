## Problem Statement 


## Solution

```python
# Provide your solution here.

def function(N):
    dic = {}
    count = 0
    for i in N:
        if i in dic:
            dic[i] += 1
        else:
            dic[i] = 1
    for key, value in dic.items():
        if value == max(dic.values()):
            return (f"{key}:{value}")


n = input("enter a list of values = ").split()
result = function(n)
print(f"{result}")
