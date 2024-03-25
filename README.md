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
Program to find the square root for the given number(newton's method) using function.
def newton(num,numiters=100):
    a=float(num)
    for i in range(numiters):
        num=0.5*(num+a/num)
    return num
a=int(input())
print("Square root of the number:",newton(a))
Developed by:THARUN V K 
RegisterNumber:212223230231  
*/
```

## Output:
![Screenshot 2024-03-25 170859](https://github.com/tharunkumaran2006/Square-root-of-a-number/assets/151625188/9b894406-c088-44f5-8883-dbf61bac4d8b)



## Result:
Thus the program to find the square root for the given number(newton's method) using function is written and verified using python programming.
