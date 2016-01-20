#Keyboard Input

Creating variables that never change seems very limiting.  Most programs do not just run on their own.  Usually they will request input from the user, either in the form of keyboard input (shown here), or file input.  See examples below on how to give values to a variable based on user keyboard input.

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

In the example above, we use ```input()``` to get information from the user.  Inside the brackets of the function is the question that pops up to prompt the user on what information we are looking for.

###Numeric Conversion of Strings

You'll also notice some other new functions that are included above: ```int()``` and ```float()```.  These functions will convert the information inside their brackets into their respective number format (```int()``` turns the value into an integer if possible, and ```float()``` turns the value into a float number if possible).  If for some reason, the values in the brackets are not numeric in nature, then the function will cause an error to occur.