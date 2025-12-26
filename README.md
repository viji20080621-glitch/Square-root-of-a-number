# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Assign number_iters = 100 in the function to perform 100 iteratios.
3. Set i = 0.
4. Calculate  number = 0.5 * (number + a / number) for 100 iterations.
5. Return number

## Program:
# Program to find the square root for the given number(newton's method) using function.
# Developed by: Vijiyalakshmi A
# RegisterNumber: 212225240185 

```
def newton(n,nt=100):
    a=float(n)
    for i in range(nt):
        n=0.5*(n+a/n)
    return n
a=int(input())
print("Square root of the number:",newton(a))
```

## Output:

<img width="1115" height="388" alt="Screenshot 2025-12-26 205615" src="https://github.com/user-attachments/assets/04d60dc5-57f9-45fa-a153-224780532b61" />

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
