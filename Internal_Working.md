Variable have no datatypes, but refrence have data types

# Python Reference Counting and Memory Management

## Overview

Python uses a reference counting mechanism to manage memory for objects. This system helps track the number of references to each object, aiding in memory management and object lifecycle.

## How Reference Counting Works

1. **Object References**:
   Every Python object has an associated reference count, which tracks how many references point to that object.

2. **Incrementing the Count**:
   Each time a new reference to an object is created, its reference count is incremented.

3. **Decrementing the Count**:
   When a reference is deleted or goes out of scope, the reference count is decremented.

4. **Object Deletion**:
   When an object's reference count drops to zero, it means there are no more references to that object. At this point, Python's garbage collector can safely deallocate the object's memory.

### Example

```python
a = [1, 2, 3]  # Create a list object with a reference count of 1
b = a          # `b` now references the same list object, increasing the count to 2
del a          # `a` no longer references the list object, reducing the count to 1
del b          # `b` no longer references the list object, reducing the count to 0
# At this point, the memory for the list object is deallocated
```

String and Integer is late decolation
