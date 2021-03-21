# assignment-python-programming-2

1.write a Python program to convert kilometers to miles?
 
code 
 
KM=int(input(print("enter the distance =")))
print("the value of kilometer in miles ",KM*0.621371)

output

enter the distance =10
the value of kilometer in miles  6.21371


2. Write a Python program to convert Celsius to Fahrenheit?


code

print("the value of temperqature in farhenite",(9/5)*C+32)
C=int(input(print("enter the temperature in celcius=")))
print("the value of temperqature in farhenite",(9/5)*C+32)


Output

enter the temperature in celcius=100
the value of temperqature in farhenite 212.0




3. Write a Python program to display calendar?
  
  
code

import calendar
y = int(input("Enter year: "))
m = int(input("Enter month: "))
print(calendar.month(y, m))

output



Enter year: 2002
Enter month: 3
     March 2002
Mo Tu We Th Fr Sa Su
             1  2  3
 4  5  6  7  8  9 10
11 12 13 14 15 16 17
18 19 20 21 22 23 24
25 26 27 28 29 30 31

4. Write a Python program to solve quadratic equation?

 code 
 
import cmath as cm
a=int(input("the coeff of X^2"))
b=int(input("the coeff of X"))
c=int(input("the independent term"))
D=(b**2)-(4*a*c)

sol1 = (-b-cm.sqrt(D))/(2*a)
sol2 = (-b+cm.sqrt(D))/(2*a)
print("the {} and {} solution of the quadratic eqn".format(sol1,sol2))


​
the coeff of X^21
the coeff of X-7
the independent term-60
the (-5+0j) and (12+0j) solution of the quadratic eqn

5 . Write a Python program to swap two variables without temp variable?
code 

x=int(input("the first value  (x) "))
y=int(input("the second value (y)"))
x=x+y
y=x-y
x=x-y
print("the swapped x is {} and swapped y {} ".format(x,y))


output 



the first value  (x) 10
the second value (y)20
the swapped x is 20 and swapped y 10
