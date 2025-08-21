# Dunder Methods in Python

**Dunder methods** (short for *double underscore methods*) are **special methods** in Python.  
They always **begin and end** with double underscores, such as:

- `__init__`
- `__str__`
- `__len__`

---

## Key Points
- These methods are **not meant to be called directly** in most cases.
- Python **internally calls them** when certain operations are performed.
- They help in customizing the **behavior of objects**.

---

## Examples

### 1. `__init__`
Called when a new object is created.  
```python
class Person:
    def __init__(self, name):
        self.name = name

p = Person("Narayan")  # __init__ is called here
```

###  2. __str__
Defines how the object is represented as a string.

```
class Person:
    def __init__(self, name):
        self.name = name
    
    def __str__(self):
        return f"Person({self.name})"

print(Person("Narayan"))  # Calls __str__ → Person(Narayan)
```
