# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
## Step1: 
Define a function.
## Step2:
Assign number_iters = 100 in the function to perform 100 iteratios.
## Step3:
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
## Step4:
Return number

## Program:
# Program to find the gcd of number using functions
# Developed By: HARIHARAN J
# RegisterNumber: 23011967
```
n=int(input())
a=0.5*n
b=0.5*(a+n/a)
while b!=a:
    a=b
    b=0.5*(a+n/a)
print("Square root of the number:",a)

```

## Output:
![image](https://github.com/HariharanJayavel/Square-root-of-a-number/assets/144870546/7da645d5-1b08-4a00-ab76-6d9be1c97329)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
