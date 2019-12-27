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

## Accessing a Word from a String

Instead of a single character, we can also access a part of a string. We can do so by specifying initial and final index of the part of the string or the substring we want to access using a colon (:). It can be considered to be iterating a part of the string.

> A substring is the fundamental part of a string. In simple words, it's a subset of a string. It may be a single character, a part of a word or a word itself.

```python
# A Python program to demonstrate how to access a word from a string

sentence = "This is a sentence"

# accessing second word from the sentence
print(sentence[5:7])  # the final index is one more than to be printed

# accessing last word from the sentence
print(sentence[10:])  # will iterate till the the end

# accessing last word from the sentence
print()sentence[:4]  # iterating from starting to index 4
```
