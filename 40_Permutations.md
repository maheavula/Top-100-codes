## Problem Statement 

Which n people can occupy r seats in a classroom in Python

Here, we will discuss program for Permutations In Which N People Can Occupy R Seats in python .In this python program, we will be defining the number of ways in which N number of students can occupy R number of seats. Take an example Ten friends enter the classroom late and all the seats are occupied by toppers of the college and now only Six seats are available so in how many ways are those Ten friends will occupy Six seats although 4 students have to leave the classroom. We will use math library for factorial function in building of this program.

## Solution

```python
# Provide your solution here.
def factorial(N):
    fact = 1
    for i in range(1,N+1):
        fact *= i
    return fact


n = int(input("enter a number = "))
r = int(input("enter a number = "))
result = factorial(n) // factorial(n-r)
print(f"{result}")
