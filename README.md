# PYTHON-BASIC-ASSIGNEMNTS

# Assignment_1 Solutions

SUBMITTED BY: SWAPNIL GOSAVI

# Q.1) In the below elements which of them are values or an expression ? eg:- values can be integer or string and expressions will be mathematical operators.
Ans.1 )There are total 4 values & 3 Expression are available here , that are 
Values are = ( * , 'hello' ,  -87.8  , 6 )
Expression are =  ( - , / , + )

# Q.2) What is the difference between string and variable?
Ans 2)A Variable is a container to store value in them and a String is a type of Values you would 
store in a Variable. A String is usually enclosed with " ".

# Q.3) Describe three different data types.
Ans.3)Three Different Data Type are :-

a) Integer Data Type :-Integer Data Type is represented with the help of int class.
It consists of positive or negative whole numbers (without fraction or decimal).

b) Float Data Type :- Float Data Type is represented with the help of float class.
It consists value which has Decimal point is Known as Float.

c) String Data Type :- String Data Type is represented with the help of Str class.
 Strings has stored Alpha-Numeric value.

# Q.4) What is an expression made up of? What do all expressions do?
Ans 4) Expression is made up of mathematical operators.
Various Types of Mathematical Operation are as follow :-

a) Summation Operator ('+') :- Summation Operator is used to add two values / operand.
eg :- 3+4 =7

b) Subtraction Operator ('-') :- Substraction Operator is Used to Substract two values / operand.
eg :- 8-2 =6

c) Multiplication Operator (' * ') :- Multiplication Operator is used to Multiply two Values / operand.
eg :- 5 * 3 =15

d) DiVision Operator ('/') :- Division Operator is used to divide left operand with the right and the result is in Float.
eg :- 7/2 =3.5

e) Exponential Operator (' ** ') :- Left operand raised to the power of right.
eg :- 2 ** 3 =8

f) Modular Operator ('%') :- Remainder of the division of left operand by the right.
eg :- 5%2 =1

g) Floor Division Operator ('//') :- Division that results into whole number adjusted to the left in the number line.
eg :- 7//3 =2



# Q.5) This assignment statements, like spam = 10. What is the difference between an expression and a statement?

Ans.5) Expression is made up of mathematical operators while Assignment Statement is used to assign the values to variables.
 
 
# Q.6) After running the following code, what does the variable bacon contain?

Ans.6)

bacon = 22, 

bacon + 1

Output :-
Variable Bacon Contain = 23



# Q.7) What should the values of the following two terms be?


Ans.7) 

'spam' + 'spamspam'  =   'spamspamspam'

'spam' * 3           =   'spamspamspam'



# Q.8) Why is eggs a valid variable name while 100 is invalid?


Ans.8)

As per python,Variable names cannot begin with a number. The python rules for naming a variable are :-

Variable name must start with a letter or the underscore character.
Variable name cannot start with a number.
Variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, & _ ).
Variable names are case-sensitive.
The reserved words(keywords) cannot be used naming the variable.


Now,

eggs is a valid Variable name because variable can start with Alphabet.

but

100 is an Invalid Variable name because variable can't start with numeric value.



# Q.9) What three functions can be used to get the integer, floating-point number, or string version of a value?


Ans 9)

The int() , float() and  str()  functions will evaluate to the integer,floating-point number,string version
of the value passed to them.



# Examples:
print('int(10.0) -> ',int(10.0)) # int() function converts given input to int
print('float(10) -> ',float(10)) # float() function converts given input to float
print('str(10) -> ',str(10)) # str() function converts given input to string

# Q.10) Why does this expression cause an error? How can you fix it?            

# 'I have eaten' +  99  + 'burritos'


Ans 10)

This cause of error is 99 because 99 is not a string. 
99 must be typecasted to a string to fix this error. 
The correct way of representing is mentioned below:

Input:

'I have eaten ' + str(99) + 'burritos.'

Output:

'I have eaten 99 burritos.'


print('I have eaten '+str(99)+' burritos')
