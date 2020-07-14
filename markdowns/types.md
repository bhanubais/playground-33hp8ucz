# Types

There are several ways to classify languages, here we will talk about typing.
A variable is an identifier that will store a value. We saw it before, but in python whatever the name of your variable, you can assign it what you want.
Python is what we call a language with strong dynamic typing. In fact, when you create a variable, you don't have to specify the type.

Example:

```python
a = 5
a = "BLABLA"
```

It will itself determine the type when you assign it a value.

In python, there are several types:

* String (character strings). The variable `a` above is suddenly of type str (this is called `String`).
* The booleans. It is actually a type to define the true and the false. True is represented by `True` and false by `False`. Remember the capital, it is sometimes deceitful.
* The int (integers). Relative numbers are represented in this type. The numbers `3` and `-5` will be int :)
* We will see later on :)

__attention__: If you mix types through `+` or `-`, python won't let you, so be sure what your variables contain :)


# Data structure

Now that we have seen the types, we can speak of more complex structures. It's fun to play with variables, but often we don't use that.

We can find information through data structures. In python, there are three: tuples, lists and dictionaries.

Note that this is not a type, but a data structure. So you can nest them as much as you want. A list can contain a tuple which itself contains a list.

## Tuples

A tuple is a particular data structure. See it as a whole. In fact, you can stick elements together.

```python
t = (0, "a")
```

Here the variable t is a set, the first element is an integer (0) and the second is the letter `a`.

Internal elements can be accessed through the notation `t [index]`.
The index is the index of the element in the tuple.

__attention__: In 99.99% of languages, we start counting at 0 :)

So, to access the first element of the tuple t:

```
t [0] => 0
t [1] => "a"
```

## The lists

Lists, or tables, depending on how you like to call it, are a capital structure in python.

You can have a list of integer lists, or a list of anything and everything. We can have several types in the same list.

We create a list of square brackets:

```python
list = [] # empty list
list = [1, 2, 3] # list containing 1, 2 and 3
```

The lists have no size limit, you can add as many elements as you want.

To add an element at the end of the list there is the `append` function. It is different from the functions you have used so far, it is used directly on the list. We will see later why.

```
list = []
list.append (55)
```

I strongly advise you to read the Sequential types section on the official documentation [https://docs.python.org/fr/3/library/stdtypes.html#sequence-types-list-tuple-range](https://docs.python.org/fr/3/library/stdtypes.html#sequence-types-list-tuple-range).

## Dictionary

Dictionaries are a data structure by key / value. Unlike a list where we use indices, we use keys to access the elements. We can therefore organize them better.

Keys can be anything you want. A character string, an integer, whatever. The dictionary size is "unlimited". After creating it, you can add elements.

We create a dictionary like this:

```python
dictionary = {}
dictionary = {"first name": "River", "name": "Song"}
dictionary ["age"] = 18
```

Here, we created an empty dictionary on the first line. In the second, we create a dictionary with 2 keys ("first name", and "last name"). Then in the third line, we added a new entry, whose key is "age", and the value 18.


__important__: There are functions on lists and dictionaries (add / remove .etc). We'll see it all together later.