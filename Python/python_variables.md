Variables, Expressions & Statements
----

Below are explanations and sample programs to show the basics of Python regarding variables, expressions & statements.

###Documentation & Mathematics

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



* Create a program that uses order of operation in order to calculate an answer.  Your program should print out the equation, and the calculated answer to the equation.  Your equations to work with are below, and an example is just below that as well.  Save the file as '008.py'
  * 2 + 4 x 5
  * 2 x 6 - 6 / 2
  * 9 + 2
  * 3 [ ( 2 + 12) - 2 ( 5 - 1 ) ]

```python
print ('1 + 2 x 3 / (4 + 2) = ' + str(1+2*3/(4+2)))

>>> 1 + 2 x 3 / (4 + 2) = 2
```

####Variables

Variable store data in temporary locations in memory.  The types of data they can store include numbers, text, and beyond.  Variable vary (hence their name) and are not constant as the program plays out.  Variable names can contain characters, digits, and underscores, but should **always** be named something that is understandable to what the variable is doing.  When comparing variables named "n" and "numberOfCars", it is much easier to tell what the variable is doing based on having the full word available.  A naming convention we will be using in this class for variables is called "Camel Case", where each new "word" in a variable's name would start with a capital letter (like the example "numberOfCars").

To assign a value to a variable we use the "=" such as:
```python
numberOfCars = 3
```

* Create a program that assigns the value 42 to a variable called "theMeaningOfLife", then prints out "The meaning of life is: <value of theMeaningOfLife variable>".  See example below.  Save this file as 'var001.py'
```python
numberOfCars = 3
print ('The number of cars in the parking lot is' + str(numberOfCars))

>>> The number of cars in the parking lot is 3
```

* Modify program 'var001.py' so that it prints out theMeaningOfLife * 2.  Save the file as 'var002.py'.

* Create a program that has three variables (a, b, c) that contain the values (2.2, 3.3, 4.2) respectively.  Print the sum of all three values.  See example below. Save the file as 'var003.py'
```python
a = 1
b = 2
c = 3

print ('a + b + c = ' + str(a + b + c))

>>> a + b + c = 6
```

####Keyboard Input
Creating variable that never change seems very limiting.  Most programs do not just run on their own, and request input from the user to get values.  See examples below on how to give values to a variable based on user input.

```python
#Getting a string value from the user
name = input("Enter your name: ")

#Getting an integer value from the user
age = int(input("Enter your age: "))  #the int( ) forces the value to be an integer

#Getting a float value from the user
salary = float(input("Enter your salary: "))

#Outputting information based on the values above
print ('Hello, ' + name + '.  I noticed that you are ' + str(age) + ' years old, and have a salary of ' + str(salary) + '.')

>>> Enter your name: Mr. Seidel
>>> Enter your age: 100
>>> Enter your salary: 1000
>>> Hello, Mr. Seidel.  I noticed that you are 100 years old, and have a salary of 1000.
```

* Create a program that asks the user for 3 integer inputs, then output the sum of the numbers.  See example below.  Save the file as 'var004.py'

```python
#code omitted, only sample output given

>>> The sum of 3, 4, and 6 is 13
```

* Create a program that asks for your weight in kilograms, then outputs your equivalent weight in pounds.  Save the file as 'var005.py'

* Create a program that prompts for the length, width, and height of a box.  Calculate and output the surface are and the volume of this box.  Save the file as 'var006.py'

* Create a program that prompts for a name, address, city, country, and postal code.  Use appropriate variable names for all variables.  Print out the information as though it were an address label.  See [this](http://rlv.zcache.ca/canada_maple_leaf_flag_gray_and_black_design_label-ra2922e7f29604aa5af6d84b0298c203b_v1130_8byvr_324.jpg) image as a reference if you don't know how the wording should be set up.  Save the file as 'var007.py'

Submissables
------------
Do **not** submit any of the work from this section.  Your teacher will randomly choose a few programs to evaluate.

Due Date(s)
----------
Marking will begin on December 1st


#####Credits
Most of the work here is based on the work written by Peter Beens found throughout [this website](http://www2.beens.org/ics/python)
