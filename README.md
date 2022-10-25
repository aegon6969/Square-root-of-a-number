# Find the square root of a number

## AIM:
To write a program to find the square root of a number.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
### Step1: 
Define a function.
### Step2: 
Assign number_iters = 100 in the function to perform 100 iteratios.
### Step3: 
Set i = 0.
### Step4: 
Calculate  number = 0.5 * (number + a / number) for 100 iterations.
### Step5: 
Return number

## Program:
```python
Program to find the square root for the given number(newton's method) using function.
Developed by: M>Rishi
RegisterNumber:  22000276
n1=int(input()) 
x=1
for i in range(100):
    x = 0.5*(x + n1/x)
print("Square root of the number:",x)

```

## Output:
![gcd of two number](/sqrt%20of%20a%20number.png)


## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
