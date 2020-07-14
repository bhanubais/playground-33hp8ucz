# Procedures and functions

## Definitions

A procedure is a series of actions that return nothing.
A function is a procedure that returns something.

I will imagine like this:

* If I ask someone to add, it's a procedure, but if I ask for the result, it's a function.

For example, a classic procedure is to print something (`print`). It doesn't return a result in your code, but it does something. Well, a procedure is when you ask your turtle to do something.

For example, a classic function is precisely the example of addition. We ask to calculate a + b & we want the result.


The reason we write procedures and functions is to be able to cut the code into small pieces. We can suddenly write a function which does a processing so as not to have to repeat the code. If I want to be able to do the following calculation: `f (x) = x * x + 55`, and I want to calculate the result for 10 different values, it's easier to have a function :).

In python, there are no procedures (not typed). In fact, as I said above, a procedure is a function that returns ** nothing **. In python, nothing has a notation, it is type `None`.

How can we send something back? The keyword return is there for that. If you don't put it, python will automatically return `None`.

Take the example of an addition:

```python
def add (a, b):
  c = a + b
  return c
```

Here we have defined a function, which takes 2 arguments (a and b). Then anything that is a tab or more after the line of the keyword `def` is in the function.

For example :

```python
def add (a, b):
  c = a + b
  return c
a = 5
```

The line `a = 5` is not in the add function. The latter (the function), calculates the sum of a and b, and stores it in a variable c. Then it returns the value of c with the return.

## Function call

Now that we have written functions, we must be able to use them. You can call functions using its identifier, and parentheses.

```python
input ()
```

In progress, you used the `input` function to wait for user input, and suddenly pause your program.

In the parentheses, we put the arguments. There are several ways:

* Or in the order `add (5, 2)`
* Either by specifying the variables `add (a = 5, b = 2)` or `add (b = 2, a = 5)`

Variables can be written in place of numbers:

```python
a = 5
b = 8
add (a, b) # or add (b, a)
```
The returned value is stored directly after the function call, so we can nest them:

```python
add (5, add (2, 3)) # 5 + (2 + 3)
```

We can even recover the result through the classic assignment:

```python
a = 5
result = add (a, 5)
```

The result variable therefore contains `10`.