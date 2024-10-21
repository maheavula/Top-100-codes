## Problem Statement 

Number be expressed as a sum of two prime numbers in python 

Here, we will discuss the program to check whether a number be expressed as a sum of two prime number in python. Prime number is a number which only have two divisors i.e. a number which can not be divided by any other number other than 1 or itself is a prime number.

## Solution

```python
# Provide your solution here.
def function(N):
    prim_lst = []

    for i in range(2,N):
        is_prime = True
        for j in range(2,i):
            if i % j == 0:
                is_prime = False
                break
        if is_prime:
            prim_lst.append(i)
    print(prim_lst)
    pairs = []
    for i in range(len(prim_lst)):
        for j in range(i + 1, len(prim_lst)):
            if prim_lst[i] + prim_lst[j] == N:
                pairs.append((prim_lst[i], prim_lst[j]))

    if pairs:
        for prime1, prime2 in pairs:
            print(f"{prime1} and {prime2} are the prime numbers that sum to {N}")
    else:
        print(f"No prime pairs found that sum to {N}")


n = int(input("enter a number = "))
result = function(n)
print(f"{result}")
