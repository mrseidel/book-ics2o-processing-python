#Conditional Statements

A conditional statement is used to branch off, or set values, based on specific conditions.  When we were working through our flowcharting work, the diamond was the symbol we used in this situation.

In the context of programming, we use conditional statements when there is a comparison required.  For example, if we wanted to compare a variable with certain numerical values, we can see if that number is positive, negative, or has a value of zero.

```python
number = int(input("Enter a number"))
if (number > 0):
  print (str(number) + ' is a positive number!')
elif (number < 0):
  print (str(number) + ' is a negative number!')
else:
  print (str(number) + ' has no value.')
```

Along with basic ```if()``` statements, the example above included two other options regarding how conditional statements work.  You will notice that there is an ```elif()``` statement.  This can only be used if there is a preceding ```if()``` statement.  ```elif()``` is the way Python writes the statement _else if (this occurs) then_.  The last statement in the example above is the ```else:``` statement.  This is used as a type of _catch all_ statement.  It means _if nothing is true from the above ```if()``` and ```elif()``` statements, then complete this instead_.

As you can see in the above example there are multiple ways to compare a value (we used the 'greater than' and 'less than' symbols).  Below is a chart that shows all of the comparison operators available in Python.

|Operator| Meaning|
|-----|-----|
|<| less than|
|<=| less than or equal to|
|>| greater than|
|>=| greater than or equal to|
|==| equal|
|!=| not equal|

