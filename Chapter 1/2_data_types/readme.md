**Data Types**
-------
1. ***Integers***
    - In python integers are whole numbers without decaimal point.
    - They can be either positive or negative and commonly used for counting and performing arithemtic operations such as Addition, Substraction, Multiplication, Division.
2. ***Floats***
    - These represents decimal numbers, offering more precision that integers.
3. ***Strings***
    - Sequenece of characters enclosed within single or double quotes.
    - Strings are normally used for manipulating textual informations.
    - Strings can be joined (concatenated) using plus(+) operator.
    - Strings has power built-in methods that lets you mofidy and analyze text effeciently.
4. ***Boolean***
    - Represents binary values: True or False.
    - Booleans are crucial for logical operatrions and comparisions.
    - Boolean can also be result of logical operations like AND, OR, ot NOT.

**Arithmetic and String Operations**
------------

***Basic operations on Numerical Data***

1. **Addition:** Use the + operator to add numbers
```python
x = 8
y = 6
result = x + y
print(result) # Output: 14
```
2. **Substraction:** Use the - operator to subtarct one number from another
```python
x = 8
y = 6
result = x - y
print(result) # Output: 2
```
3. **Multiplication:** Use the * operator to multiply numbers
```python
x = 8
y = 6
result = x * y
print(result) # Output: 48
```
4. **Division:** Use the / operator divide numbers and get a float or // for integer division.
```python
x = 8
y = 6
result = x / y
print(result) # Output: 1.3333333333333333
result = x // y
print(result) # Output: 1
```
***String Concatination***

To concatinate the string use the + operator.
```python
getting = "Hello"
name = "Alice"
message = greeting + ", " + name + "!"
print(message) # Output: Hello, Alice!
```
***Displaying Output with Print Function***

print() function is used to displaying informations to the user.
```python
# Printing a single item
print(100) #Output: 100

# Printing multiple items
a = 5
b = 10 
print("The value of a is ", a , "and the value of b is ", b) # Output: The value of a is 5 and the value of b is 10

# Using formatted string
name = "Bob"
age = 26
print(f"{name} is {age} years old") # Output: Bob is 26 years old
```
***Gathering User Input With the input Function***

Your program often need to be interact with the user by collecting user input. The **input** function reads the line of text entered by the user.
```python
user_name = input("Enter your name: ")
print(f"Hello, {user_name}") # Output: If the user entered is 'John', output will be: Hello, John
```
You can also convert the input to other data type such as integers or floats if needed.
```python
user_age = int(input("Enter your age: ")) # Converts input to integers
print(f"You are {user_age} years old") # Output: if the user entered is 30, output will be You are 30 years old
```
