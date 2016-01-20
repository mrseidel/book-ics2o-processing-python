

###Variables

Variables store data in temporary locations in memory.  The types of data they can store include numbers, text, and beyond.  Variables vary (hence their name) and are not constant as the program plays out.  Variable names can contain characters, digits, and underscores, but should **always** be named something that is clear and understandable.  When comparing variables named "n" and "numberOfCars", the latter is easier to know what its purpose is.  A naming convention we will be using in this class for variables is called "Camel Case", where each new "word" in a variable's name would start with a capital letter, while the very first letter is lowercase (like the example "numberOfCars").

To assign a value to a variable we use the "=" such as:
```python
numberOfCars = 3
```

If we were to use a variable to print out information, we could do the following:
``` python  
numberOfCars = 3
print ('The number of cars in the parking lot is' + str(numberOfCars))

>>> The number of cars in the parking lot is 3
```

###More on the str() function

The ```str()``` function changes whatever data type you are using (for example, an integer, or float value) into a string.  A string is used whenever you print off information to the screen.  For strings, whenever you add them using the ```+``` symbol, it actually _[concatenates](https://en.wikipedia.org/wiki/Concatenation)_ the data.