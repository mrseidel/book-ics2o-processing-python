

###Variables

Variables store data in temporary locations in memory.  The types of data they can store include numbers, text, and beyond.  Variables vary (hence their name) and are not constant as the program plays out.  Variable names can contain characters, digits, and underscores, but should **always** be named something that is clear and understandable.  When comparing variables named "n" and "numberOfCars", it is much easier to tell what the variable is doing based on having the full word available.  A naming convention we will be using in this class for variables is called "Camel Case", where each new "word" in a variable's name would start with a capital letter (like the example "numberOfCars").

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



Submissables
------------
Do **not** submit any of the work from this section.  Your teacher will randomly choose a few programs to evaluate.

Due Date(s)
----------
Marking will begin on December 1st


#####Credits
Most of the work here is based on the work written by Peter Beens found throughout [this website](http://www2.beens.org/ics/python)
