Here's a Python program to print a little story using 'print()' function.

```python
print("There was a man named Saurabh who was 30 years old")
print("He liked his name Saurabh")
print("But hated to be 30 years old")
```

Suppose, we wanted to change the name and age of the person. We would have to go change the required data wherever it appears. It's where the importance of variables arises. A variable is a container which can store a particular data. If we change the data in a variable, data changes wherever that variable occurs reducing unnecessay hard work.

**Syntax-**

```python
variable_name = data
```
Now, the type of data we store in a variable specifies the data type of a variable. A data type of a variable is the type of data stored by a variable. Some most used data types are-

1) String(str) - A string of characters

```python
a = "Python is a programming language"
```
> **A string is always declared with double quotes.**

2) Integer(int) - An integer number

```python
a = 10
```

3) Float(float) - A decimal number

```python
a = 1.5
```
4) Double Float(double) - A decimal number with more [significant digits](https://en.wikipedia.org/wiki/Significant_figures).

```python
a = 1.4998
```

5) Boolean(bool) - Boolean True or False

```python
a = True
```
> **There's a great difference between `a = 10` and `a = "10"`. While the former is an integer, the latter is a string. Mathematical operations can't be performed on a string.**

If you recall our first program, to print a string, we wrote the following code.

```python
print("Hello World!")
```
What we did here is printing a string. Another way to accomplish this is by using a variable. A variable can be printed as 'print(variable_name)' which prints the value of the variable.

```python
# A program to print 'Hello world!'
string  = "Hello World!"
print(string)
```

#### Output-

```
Hello World!
```

If we want to use a string along with a variable, we may do as in the following program.

```python
# A python program to show concepts of variables
color = "Red"
number = 7
print("My favourite color is " + color)  # concatenating two strings
print("My favourite number is " + str(number))  # converting an integer into a string to concatenate

```

#### Output-

```
My favourite color is Red
My favourite number is 7
```
#### Explanation-
In the first print statement, string 'color' has been concatenated with another string ' "My favourite color" '. In the second print statement, we were trying to concatenate a string with an integer, which is not possible and will produce an error. To remove such an error, we'll have to convert the integer into a string as 'str(var_name).

> **Concatenation of string is combining of two or more strings with each other. To read more about concatenation of strings, click [here](https://en.wikipedia.org/wiki/Concatenation).**

Coming to back to our story, using the above concepts we can change our code as follows.

```python
name = "Saurabh"
age = "30"
print("There was a man named" + name + " who was " + age + " years old")
print("He liked his name " + name)
print("But hated to be " + age + " years old")
```
#### Output-

```
There was a man named Saurabh who was 30 years old
He liked his name Saurabh
But hated to be 30 years old
```
 
 Now, if we want to edit the name in the story, we can do that by just editing the name in the variable `name`.
