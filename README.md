# functions-assignment
#q1
from math import pi
r = float(input ("Input the radius of the circle : "))
print ("The area of the circle with radius " + str(r) + " is: " + str(pi * r**2))
#q2
n = int(input("Enter any number: "))
sum1 = 0
for i in range(1, n):
    if(n % i == 0):
        sum1 = sum1 + i
if (sum1 == n):
    print("The number is a Perfect number!")
else:
    print("The number is not a Perfect number!")
#q3
def times_tables(n,t=1):
    if t == 13:
return
    print(str(n) + " x " + str(t) + " = " + str(n*t))
    times_tables(n, t+1)
n=12
times_tables(n)
#q4
def power(a,b):
    if(b==1):
        return(a)
    if(b!=1):
        return(a*power(a,b-1))
a=int(input("Enter a: "))
b=int(input("Enter exponential value: "))
print("Result:",power(a,b))
#q5
d={}
def factorial(n):
    if(n <= 1):
        return 1
    else:
        return(n*factorial(n-1))
n = int(input("Enter number:"))
print("Factorial:")
print(factorial(n))
d={"factorial(n)"}

