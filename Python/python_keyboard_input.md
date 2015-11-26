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

* Create a program that asks the user for 3 integer inputs, then output the sum of the numbers.  See example below.  Save the file as 'var004.py'

```python
#code omitted, only sample output given

>>> The sum of 3, 4, and 6 is 13
```

* Create a program that asks for your weight in kilograms, then outputs your equivalent weight in pounds.  Save the file as 'var005.py'

* Create a program that prompts for the length, width, and height of a box.  Calculate and output the surface are and the volume of this box.  Save the file as 'var006.py'

* Create a program that prompts for a name, address, city, country, and postal code.  Use appropriate variable names for all variables.  Print out the information as though it were an address label.  See [this](http://rlv.zcache.ca/canada_maple_leaf_flag_gray_and_black_design_label-ra2922e7f29604aa5af6d84b0298c203b_v1130_8byvr_324.jpg) image as a reference if you don't know how the wording should be set up.  Save the file as 'var007.py'