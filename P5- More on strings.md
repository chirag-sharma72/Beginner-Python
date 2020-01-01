Until now, we've been printing texts using `print()` function. Generally, anything printed with quotes is a string of characters. Following are some ways to print a string.

```python
# A python program to print a string

print("My name is Rohit.")

string = "My name is Samir."
print(string)

name = "Ram"
print("My name is " + name + ".")
```

#### Output

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
print("First element: " + qoute[0])
print("Sixth element: " + qoute[5])
print("Last element: " + qoute[35])
print("Last element: " + qoute[-1])
print("First element: " + qoute[-36])
```

#### Output

```
First element: A
Sixth element: e
Last element: .
Last element:  .
First element: A
```

## Accessing a Word in a String

Instead of a single character, we can also access a part of a string. We can do so by specifying initial and final indices of the part of the string or the substring we want to access using a colon (:). It can be considered as iteration of a part of a string.

> A substring is the fundamental part of a string. In simple words, it's a subset of a string. It may be a single character, a part of a word or a word itself.

```python
# A Python program to demonstrate how to access a word from a string

sentence = "This is a sentence"

# accessing second word from the sentence
print(sentence[5:7])  # the final index is one more than to be printed

# accessing last word from the sentence
print(sentence[10:])  # iterating from index 10 till the end

# accessing first word from the sentence
print(sentence[:4])  # iterating from the beginning to index 4
```

## Reversing and Stepping in a String
A string can be reversed by a method called stepping by adding another colon after specifying initial and final indices. In stepping, a number is specified after the colon which determines the number (and direction) of steps.

```python
# A python program to demonstrate reversing and stepping in a string

fav_dessert = "I love ice-cream."

# reversing the string
print(fav_dessert[::-1])  # reverse stepping

# stepping in the string
print(fav_dessert = [::2])  # stepping with steps of 2 (printing half of the letters)

# stepping and reversing
print(fav_dessert = [21:14:-3])  # stepping reversively in steps of 3
```

#### Output

```
.maerc-eci evol I
Ilv c-ra.
.e-iv 
```

