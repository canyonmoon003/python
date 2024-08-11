*Question 3*
------
With a given integral number n, write a program to generate a dictionary that contains (i, i x i) such that is an integral number between 1 and n (both included). and then the program should print the dictionary.
------
```python3
n=int(input())
answer={i : i*i for i in range(1,n+1)}
print(answer)
```