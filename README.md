# Exp-2a- Find the GCD of two numbers
## Date-29.08.2023
## AIM:
To write a program to find the GCD of two numbers using function.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner

## Algorithm
1. Define a function.
2. Get the two numbers from the user.
3. Compare the two values, to find the smaller number.
4. Use for() and if() loop to find the GCD of the two numbers.

## Program:
```
/*
Program to find the gcd of two number using function.
Developed by: KISHORE KUMAR U
RegisterNumber:  23000800
*/
```def gcd():
    n1,n2=int(input()),int(input())
    if n1>n2:
        smaller=n2
    else:
        smaller=n2
    for i in range(1,smaller+1):
        if (n1%i==0 and n2%i==0):
            hcf=i
    print("GCD of two numbers is:",hcf)
```

## Output:
![image](https://github.com/Kishorekumar22060/GCD-of-two-numbers/assets/141472136/70ad1ee6-0719-46e4-9a1f-c5b62e9abd77)



## Result:
Thus the program to find the GCD of two numbers is written and verified using python programming.
