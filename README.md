# Python-notes

Python:

Module1:
-------------------

Single line comments and multiline comments:


So in python we use "#" for single line comments

#This is single line comment in python

Were as we use """  """ this for multiline comments 

"""
This is vivek
learning single line and multiline comments in python
started with this topic
"""

==========================================================================================================================================================



Keywords:

there are nothing but some reserved words in python which have some special meanings All keywords in python are in lowercase except the True and False.


some of the keywords in python are:

True , False , and , or ,not ,if ,elif,else,for ,while ,break ,def etc



Identifiers:


Identifiers are nothing but userdefined names given to variable , function , class and modules. They are also case sensitive.


it cannot be and keyword or else it cannot be start with special character except "_" (underscore) and should not start with numbers also and also should not contain white spaces.


Variables:

Variables are nothing but which is used to store the values . It is like a memory location which is used to store values and can be change at any time when needed.


==========================================================================================================================================================

DataTypes:

DataTypes are nothing but the type given to the value to identify the which operations we are performing



Numeric:
------------
Numeric data type is defined as having the numeric data it can be of three types integer, float and complex numbers

integer: It is the type which is used to store the positive and negetive numbers but not the whole numbers. ex: a=5 ,b= -5 

float :  It is the type which is used to store the values with decimal type.  --->  ex: a= 2.0 

complex numbers: It is the type which is used to store the values with complex type like real part and the imaginery part --> ex: a= 2+4j


Sequence :
------------
It is the datatype which is used to store the value in a sequence way and collection of data in similar and diffrent data types:

ex : string , list , tuple

1. string : It is nothing but collection of characters which can store the data in single and double or triple quotes

ex: a=  ' This is String example'
b= " This is string double quotes example"
c= ''' This is string triple quotes example '''

2. list :  it is same as string but collection of data in [] brackets

ex: [1,2,3] ["abc","viv","sad"]

3. tuple : it is same as list but here the collection is stored in () and here tuples are immuatble means we cannot modify after creating it 

ex: (1,2,3) ("abs","geeks","viv")

Boolean:
-------------

It is the data type contain two built-in values like True and False 

Ex : True , False

set:
----------

It is the datatype which is used to store the unordered collection of data type and are itterable and also mutable and should not have duplicate values 

ex: a= (2,3,4)

dictionary:
------------
It is the datatype which is used to store the unorderd collection and store in the form of key and value unlike other data types

a = {'viv': 24,'bin' :16}

we can access it by using its key or value 



==========================================================================================================================================================


Module2:
------------


Type Conversions:
-------------------


Type conversions are nothing but which is used to convert one type of data to another datatype.

There are two types of TypeConversions
1. Implicit TypeConversions
2. Explicit TypeConversions


Implicit TypeConversions:
----------------------------

Nothing but which is used to convert one datatype to another datatype without any user involvement which converts directly

x = 10

print("x is of type:",type(x))

y = 10.6
print("y is of type:",type(y))

z = x + y

print(z)
print("z is of type:",type(z))

x = 10

print("x is of type:",type(x))

y = 10.6
print("y is of type:",type(y))

z = x + y

print(z)
print("z is of type:",type(z))




Explicit TypeConversions:
----------------------------

Nothing but which the datatype is manually converted from one datatype to another datatype  which includes user intervention.

Ex:

a = 10.01

b = int(a)

print(" the value after convertion is " ,b)


==========================================================================================================================================================

Input and output Function:
--------------------------------


Print() : 

In Python we use print() to print the output to the user console


Input():

In Python we use input() to take the input from the user 

we use specify the type before input when taking the input from user

ex:

int(input)
float(input)
list(input)


==========================================================================================================================================================

Operators:
------------

Operators are nothing but which is used to perform on values and variables
 
 
Types of Operators:

Arithmetic operaters:
------------------------

Arithmetic Operators are nothing but which is used to perform basic operations like add,sub,division,multiplication 

# Examples of Arithmetic Operator
a = 9
b = 4

# Addition of numbers
add = a + b

# Subtraction of numbers
sub = a - b

# Multiplication of number
mul = a * b

# Modulo of both number
mod = a % b

# Power
p = a ** b

# print results
print(add)
print(sub)
print(mul)
print(mod)
print(p)

13
5
36
1
6561


Comparision Operators:
-------------------------

Comparision Operators are nothing but which is used to compare between two values like <,>,==,!=,<=,>= and output will be True or False.

# Examples of Relational Operators
a = 13
b = 33

# a > b is False
print(a > b)

# a < b is True
print(a < b)

# a == b is False
print(a == b)

# a != b is True
print(a != b)

# a >= b is False
print(a >= b)

# a <= b is True
print(a <= b)


False
True
False
True
False
True

Logical Operators:
------------------------

Python logical operaters are Logical AND , Logical OR and Logical NOT

and --> Ture if both values Satisfies
or --> Ture if One of it Satisfies
not --> Ture if the operand is false

# Examples of Logical Operator
a = True
b = False

# Print a and b is False
print(a and b)

# Print a or b is True
print(a or b)

# Print not a is False
print(not a)


False
True
False

Bitwise Operators:
-------------------------

Bitwise Operators are used to perform operations on the bits 

bitwise AND --> a & b
bitwise OR --> a | b
bitwise NOT --> ~a
bitwise XOR --> a ^ b
bitwise left shift --> a<<
bitwise right shift --> a>>

# Examples of Bitwise operators
a = 10
b = 4

# Print bitwise AND operation
print(a & b)

# Print bitwise OR operation
print(a | b)

# Print bitwise NOT operation
print(~a)

# print bitwise XOR operation
print(a ^ b)

# print bitwise right shift operation
print(a >> 2)

# print bitwise left shift operation
print(a << 2)


Output
0
14
-11
14
2
40


Assignment Operator:
-----------------------
There are nothing but which are used to assign values to the variables

ex: a=a+b or a+=b or a=a-b or a-=b

# Examples of Assignment Operators
a = 10

# Assign value
b = a
print(b)

# Add and assign value
b += a
print(b)

# Subtract and assign value
b -= a
print(b)

# multiply and assign
b *= a
print(b)

# bitwise lishift operator
b <<= a
print(b)


Identity Operators:
---------------------------

In Python we use is,is not as identitical operaters  which is used to check and compare between two values

a = 10
b = 20
c = a

print(a is not b)
print(a is c)


True
True

Membership Operators:
-----------------------------

In Python we use in , not in as membership operaters which are used to check whether the values are in sequence or not.

# Python program to illustrate
# not 'in' operator
x = 24
y = 20
list = [10, 20, 30, 40, 50]

if (x not in list):
	print("x is NOT present in given list")
else:
	print("x is present in given list")

if (y in list):
	print("y is present in given list")
else:
	print("y is NOT present in given list")


o/p:

x is NOT present in given list
y is present in given list


1. Arithmetic operaters
2. Comparision Operators
3. logical Operators
4. Assignment Operators
5. Membership Operators
6. Identity Operators
7. Bitwise Operators


Swapping of two numbers:
----------------------------------


a=10
b=20

Print("Swapping the values of a an b")

a= a+b 
b= a-b  
a= a-b    

print("value of a",a)
print("Value of b",b)


Find last digit in python:
------------------------------

num = 123

last_digit = num % 10

print ("last number is ",last_digit)


==========================================================================================================================================================

Module3:
--------------


1. Flow Controlls  --> if,else,Nested if,elif

if:
----

which is used to check the condition and if satisfies allows you to block if fails then will not enter into the block of code.

Ex: 

a=10

if a<=10:

  print("value of a is",a)

else:
------

Which is Used to check the condition and if satisfies allows to the block of code and if fails it enters to the else block

Ex: 

a=10

if a <=10:
   
   print("value of a is",a)
   
else:
   print("Value of a is less than 10")
   
Nested if :
---------------

Nested if is used to check the condition inside the condition .

Ex:

x = 10
y = 5

if x > 5:
    print("x is greater than 5")
    
    if y > 2:
        print("y is also greater than 2")
    else:
        print("y is not greater than 2")
else:
    print("x is not greater than 5")
	
	
elif:
------------

a= 10


if a>10:
  print("a value is greater than 10")
elif a<10:
  print("a value is less than 10")
else: 
  print("a value is ",a)
  
  
even odd program in python:
---------------------------

n= int(input("Enter the number"))

if n%2 == 0:
  print("even number")
else:
  print("odd number")


Leap Year Program:
---------------------------

n= int(input("enter the number"))

if n%4 == 0:
  print("leap year")
else:
  print("not a leap year")
  
  
  
2. Loops in Python 

while:
---------

while loop in python is used to check the condition and if satisfies it allows you to block of code

a=0

while (a<=10):
  print("a value is ",a)
  

range():
-----------

In Python we have range() which is used to specify the range and execute it accordingly


for i in range(1,10):
  print(i)
  
o/p: 1 2 3 4 5 6 7 8 9 10

for loop:
------------

in python for loop is used to itterate over the specify range and if range exceeds it will go out of loop

ex:

for i in range(1,5):
  print(i)
  
 o/p : 1 2 3 4 5
 
 
for else:
-------------

else block in python for forloop is used to enter the block when the for loop finishes

for i in range(1,3):
  print(i)
else:
  print("loop completed")
  
Break:
--------

In python break is used to break the block of code if condition satisfies  and comes out of loop


for i in range(1,10):
  if i==3:
    break
  print(i)


o/p: 1 2

table of a number:
---------------------

n=int(input("number"))


for i in range(1,12):

   print(f"{n}*{i}={n*i}")
 
continue:
------------

In Python continue is used when if the block of code is true then it simply skips the step

for i in range(1,10):
  if i==3:
    continue
  print(i)
  
o/p:  1 2 4 5 6 7 8 9 10

pass:
------------

In Python pass statement is used like it doesn't do nothing just it simply skips the step without doing nothing.When the Python interpreter encounters a pass statement, it simply moves on to the next statement without executing any code.




for i in range(1,10):
  if i==3:
    pass
  print(i)
  
o/p:  1 2 3 4 5 6 7 8 9 10

nested loop:
--------------------

Nested loops in python are used to itterate over the loop over loops like it is used when you are writing code in the rows and coloumns

for i in range (1,2):
  for j in range (1,2):
	print(f"{i,j}")

o/p:  (1,1) (1,2)



count digits in python:
-----------------------------

number = 1234567
count= 0

while (number>0):
 number=number//10
 count= count+1
 
print("number of digits of a number",count)


o/p: 7


for alphanumeric:
--------------------------

word = "vivek545"
count=0

for char in word:
  if char.isdigit():
    count=count+1

print("number of digits",count)

o/p:  number of digits 3
 


factorial in python:
---------------------------

f=1
n=5
for i in range(1,n+1):
    f=f*i
print(f)

o/p: 120

gcd in python:
-------------------

import math

# Example with two numbers
num1 = 36
num2 = 48

gcd_result = math.gcd(num1, num2)
print("GCD of", num1, "and", num2, "is", gcd_result)


fibnocci in python:
---------------------

n=10
a=0
b=1
print(a)
print(b)
for i in range(2,n):
    temp=a
    a=b
    b=temp+b
    print(b)
    
o/p : 0 1 1 2 3 5 8 ....

==========================================================================================================================================================

Module 4:
-------------


python functions:
---------------------

Function is nothing but a block of code which is executed when it is called
Function is like it is define by using def keyword

def myfunction():

  print("hello this is my function")
  
  


passing values through functions:
----------------------------------

def myfunction(name):
  print("my name is" ,name)
  
myfunction("vivek")
myfunction("bin")
myfunction("deck")

Paramater or Arguments :
-----------------------------


The term parameter or argument can be used with the same thing information that are passed to the function.


def exfun(firstname,lastname):
  print("frist name is " + firstname +  " "  +   "last name is"   + lastname)
  
exfun('vivek','atkuri')


keyword argements:
------------------------------


def exfun(chld1,chld3,chld2):
  
   print("name of my child" + chld3)
   
exfun(chld1 = "vivek" , chld3 = "atkuri" , chld2 = "bins")


default arguments:
--------------------------------------


def exfun(name = "vivek")

  print("name is " + name)
  
exfun("bins")
exfun("atkuri")
exfun()
exfun("vicky")

o/p :  name is bins
name is atkuri
name is vivek
name is vicky

Lambda function:
-------------------------


Lambda function is nothing but it is a anonymous function.

A lambda function can take any number of arguments , but can only have one expression.


ex:
  
x = lambda a : a + 10
print(x(5))

o/p : 15

 
x = lambda a,b: a*b
print(x(2,3))

o/p: 6

x = lambda a,b,c : a+b+c
print(x(1,4,5))

o/p: 10

Decoraters:
----------------

In Python Decarator is nothing but it is a design pattren that allows you to modify the functionality of function  by wrapping with its another function.

def outer(x):
    def inner(y):
        return x + y
    return inner

add_five = outer(5)
result = add_five(6)
print(result)  # prints 11

# Output: 11
