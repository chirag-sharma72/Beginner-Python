Having taken a quick glance of Python, it's time we get into programming. In this topic, we're going to learn how to draw a shape.


> **We strongly recommend to try it yourself before reading further.**


In 'Hello World' program, we used a `print()` function to print a statement. Now to draw a shape, we can simply use a combination of print statements. It should be kept in mind to not dive into writing a code as soon as you see a problem. Observe and analyse the problem properly and think about the solution. A language is just a way of writing a solution to the problem.

Here, our objective is to make a triangle. We'll keep the following in mind while writing the code (It solely depends on you 
the type of triangle or the shape you want to make).

![Triangle1](https://user-images.githubusercontent.com/47327461/70930730-e4258b80-205b-11ea-9f41-28231f87cbb3.png)

Our first print statement will do the task of printing the vertex of the triangle.

```python
print("   /|")
```
Such print statements will be combined to print a triangle.

```python
print("|\    ")
print("| \   ")
print("|  \  ")
print("|___\ ")
```

This can also be acheived through a single 'print()' function.

```python
print("|\    "
      "| \   "
      "|  \  "
      "|___\ ")
```

**\n is a new line character used to break the output line i.e. print a new line. It's always written with double qoutes.**

#### Output

![BTriangle](https://user-images.githubusercontent.com/47327461/71019414-46e05b00-2120-11ea-9352-94a91d53419a.PNG)

