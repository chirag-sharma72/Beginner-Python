Until now, we've been printing texts using `print()` function. Generally, anything printed with quotes is a string of characters. Following are some ways to print a string.

```python
# A python program to print a string

print("My name is Rohit.")

string = "My name is Samir."
print(string)

name = "Ram"
print("My name is " + name + ".")
```

### Output

```
My name is Rohit.
My name is Samir.
My name is Ram.
```

## Accessing an Element in a String

An element in a string can be accessed using indices. Each character (including a space) can be represented using indices where first element is at index 0, second element at index 1, and so on.


It's done by writing the string name along with square brackets with the index. An element can also be accessed using a negative index. For example, for accessing the last element, we can write `string_var[-1]`.

```python
# A python program to demonstrate how to access an element

qoute = "A friend in need is a friend indeed."
print(qoute[0])  # accessing the first element
print(qoute[5])  # accessing the sixth element
print(qoute[35])  # accessing the last element
print(qoute[-1])  # accessing the last element
print(qoute[-36]  # accessing the first element
```

### Output

```
A
e
.
.
A
```

### Accessing a Substring from a String

A substring is the fundamental part of a string.
