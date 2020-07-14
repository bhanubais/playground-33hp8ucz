# The blocks

A block is a series of actions. In python it is defined by the level of tabulation.

## Conditional blocks

Often, you have to perform one action or another depending on the value of a variable.

In python, the structure of conditional blocks are:

```
if [CONDITION]:
Instructions if true condition
...

or

if [CONDITION]:
Instructions if true condition
...
else:
Instructions if false condition
```

__important__: Note the use of the `:`, in python it is essential to put it at the end of the first line of the block :)

__note__: we will use the print function to display in the terminal :)

Small example:
```python
ta_note_en_maths = 9
if ta_note_en_maths <10:
print ("You missed")
else:
print ("Congratulations")
```

# Buckles

Often, we realize that we must perform the same action several times. It would be a shame to rewrite the same code several times, that's why loops exist.

There are two types of loops, it depends on whether you know when it stops or not.

## FOR loop

The for loop is important to understand and master. It allows you to repeat an action n times, or to browse a list in python.

You used it in your lessons to repeat an action n times, but it also allows you to browse a list of elements:

```python
list = [1, 4, 5, 6, 0]
for element in list:
print (element)
```

Above, the variable `element` will take the value in the list at each loop.


## while loop

The while loop, translated into a loop as much as in French :), is a loop to use when we don't know how many times we will do our processing.

For example, if we wait for the user to type the word: "StarLight".

```python
user_entry = "NotStartLight" # I initialize the variable
while userinput! = "StarLight": # as long as the user input is not StarLight
user_entry = input () # we ask the user to type something
print (user_entry) # We display the user input
```

This above program runs until the user has entered the requested word :).