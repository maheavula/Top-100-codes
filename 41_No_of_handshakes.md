## Problem Statement 

Maximum Number Of Handshakes in Python

Here, in this page we will discuss the program to find the maximum number of handshakes in python.

For the number of handshakes to be maximum, every person should handshake with every other person in the room i.e. all persons present should shake hands.

## Solution

```python
# Provide your solution here.
def function(N):
    return int(N*((N-1)/2))


n = int(input("enter a number = "))
result = function(n)
print(f"{result}")
