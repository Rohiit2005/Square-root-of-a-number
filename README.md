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
```
#Square root of the number
#Developed by:Rohiit.A.S
#Reference number:23010688
def newton_method(number,number_iters=100):
    a=float(number)
    for i in range(number_iters):
        number=0.5 *(number+a/number)
    return number
a=int(input())
print("Square root of the number:",newton_method(a))
```

## Output:
![exp2(b)](https://github.com/Rohiit2005/Square-root-of-a-number/assets/138849178/e86fa07a-e2da-4164-a990-3a85e0ac2b47)

## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
