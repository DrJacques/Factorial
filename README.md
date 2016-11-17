# Factorial
Factorial in Python
Define a function factorial that takes an integer x as input.

Calculate and return the factorial of that number.

Below is my code

def factorial(x):
    fact=1
    while( x!=0):
        fact= fact*x
        x=x-1
    return fact
