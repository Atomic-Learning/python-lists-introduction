Python lists are a way to create and work with ordered collections of items. This page covers Python's specific syntax for creating lists.

# Creating Lists

Lists are created using square brackets `[]`{.python} with items separated by commas:

```py-cell
fruits = ["apple", "banana", "orange"]
numbers = [1, 2, 3, 4, 5]

print(fruits)
print(numbers)
```

# Empty Lists

You can create an empty list with just empty brackets:

```py-cell
empty_list = []
print(empty_list)
```

# Lists Can Contain Different Types

In Python, a list can contain items of any type, and even mix types:

```py-cell
mixed_list = ["hello", 42, 3.14, True, [1, 2, 3]]

print(mixed_list)
```
