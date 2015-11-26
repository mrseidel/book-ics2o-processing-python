Documentation & Mathematics
----

Below are explanations and sample programs to show the basics of Python regarding documentation, mathematics, and creating basic output.

###Documentation

Every one of your programs should always include a header.  A header provides some basic information about your program including: who the author is, the date the program was last worked on, the file name, and a description of the program you are creating. A sample header is provided below:
```python
# author: Jane Doe
# date: 2013-03-26
# filename: printName.py
# description: prints user’s name to the screen
```
A basic program in Python can complete various calculations.  Below are some examples of programs.  Any line beginning with a ```>>>```is an output line after running the given program.

####Addition:
```python
print (2 + 1)

>>> 3
```

####Subtraction:
```python
print (2 - 1)

>>> 1
```

####Multiplication:
```python
print (4 * 5)

>>> 20
```

####Division:
```python
print (3 / 2)

>>> 1.5
```

####Integer Division
For integer division, the program will **truncate** the answer at the decimal point.
```python
print (4 // 2)

>>> 2
```

####Powers
```python
print (2 ** 3)

>>> 8
```

Using the above examples as an exercise create a program that uses order of operation in order to calculate an answer.  Your program should print out the equation, and the calculated answer to the equation.  Your equations to work with are below, and an example is just below that as well.
  * 2 + 4 x 5
  * 2 x 6 - 6 / 2
  * 9 + 2
  * 3 [ ( 2 + 12) - 2 ( 5 - 1 ) ]

```python
print ('1 + 2 x 3 / (4 + 2) = ' + str(1+2*3/(4+2)))
#str(___) converts the information between the parentheses into a string in order to output it properly

>>> 1 + 2 x 3 / (4 + 2) = 2
```