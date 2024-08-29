# Python_Study_material

In python, they didnt have array. Instead of use list.

Example with Python List

Here’s how the list initialization works:
```python
n = 5
dp = [0] * n
print(dp)  # Output: [0, 0, 0, 0, 0]
```python

## Understanding Python Data Types

In Python, everything is an object, including various data types. Each type is implemented as a class,
and instances of these classes are objects with associated methods and properties. Here’s a quick
overview of the core data types:

1. **Integers** (`int`): Represent whole numbers.
   - Example: `42`

2. **Floating-point numbers** (`float`): Represent real numbers with decimal points.
   - Example: `3.14`

3. **Strings** (`str`): Represent sequences of characters.
   - Example: `"Hello, world!"`

4. **Lists** (`list`): Ordered, mutable collections of items.
   - Example: `[1, 2, 3]`

5. **Tuples** (`tuple`): Ordered, immutable collections of items.
   - Example: `(1, 2, 3)`

6. **Dictionaries** (`dict`): Collections of key-value pairs.
   - Example: `{'key': 'value'}`

7. **Sets** (`set`): Unordered collections of unique items.
   - Example: `{1, 2, 3}`

Each of these data types is an instance of its corresponding class. For instance, when you create an
integer like `5`, it’s an instance of the `int` class. This object-oriented nature means that all data
types in Python have methods and properties defined by their respective classes, allowing you to
interact with and manipulate them in various ways.

## Understanding References in Mutable vs Immutable Types

Immutable Types: The reference to the object does not change; modifications result in new objects being
created. Examples include int, float, str, and tuple.

Mutable Types: The reference to the object remains the same; modifications change the content of the
original object. Examples include list, dict, and set.
