Lambda expressions are a simple single line method of creating functions in Python. Although not essential in your programming, lambda expressions can be very useful at times. They become particularly useful when you want to use a function as an argument in another function.

Here's a simple example. Imagine you wanted to create a function that took a number and added 1 to it. You could write the following:

```python
def add_one(value):
	return value + 1
	
answer = add_one(100)
```

This could be rewritten using a lambda expression:

```python
add_one = lambda value: value + 1

answer = add_one(100)
```

The general syntax for a lambda expression is to use the keyword `lambda` followed by the function's parameters, then a colon (`:`). After the colon comes the values to be returned by the function. For instance, this lambda expression can add two numbers together.

```python
add_two = lambda a, b: a + b

add_two(10, 5)
```

You can make more complicated lambda expressions and even add conditional statements into the return value. However, lambdas are best kept simple, to make sure they are readable.
