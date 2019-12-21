Here's a Python program to print a little story using 'print()' function.

```python
print("There was a man named Saurabh who was 30 years old")
print("He liked his name Saurabh")
print("But hated to be 30 years old")
```

Suppose, we wanted to change the name and age of the person. We would have to go change the required data wherever it appears. It's where the importance of variables arises. A variable is a container which can store a particular data. If we change the data in a variable, data changes wherever that variable occurs reducing unnecessay hard work.

***Syntax-***

```python
variable_name = data
```
Now, the type of data we store in a variable specifies the data type of a variable. A data type of a variable is the type of data stored by a variable. Some most used data types are-

1) String(str) - A string of characters

```python
a = "Python is a programming language"
```
> A string is always declared with double quotes.

2) Integer(int) - An integer number

```python
a = 10
```

3) Float(float) - A decimal number

```python
a = 1.5
```
4) Double Float(double) - A decimal number with more [significant digits](https://en.wikipedia.org/wiki/Significant_figures)

```python
a = 1.4998
```

5) Boolean(bool) - Boolean True or False

```python
a = True
```
> There's a great difference between `a = 10` and `a = "10"`. While the former is an integer, the latter is a string. Mathematical operations can't be performed on a string.

If ypu recall our first program, to print a string, we wrote the folowing code.

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
print("My favourite color is " + color)
```

#### Output-

```
My favourite color is Red
```
#### Explanation-
In the above program, string 'color' has been concatenated with another string ' "My favourite color" '. Concatenation of string is combining of two or more strings with each other. To read more about concatination of strings, click [here](https://en.wikipedia.org/wiki/Concatenation).

To accomplish this task, we'll create two variables, namely character_name and character_age.

 > A variable name can be whatever we want, but for a code to be readable, it's preferred to give it a logical name.
 
 > A variable can't contain spaces in between. Therefore, for a multi-word variable name, underscore (_) is used.                                                                                             ***Example-*** 'var_name'

```python
name = "Saurabh"
age = "30"
print("There was a man named" +  who was 30 years old")
print("He liked his name Saurabh")
print(""But hated to be 30 years old")
```
