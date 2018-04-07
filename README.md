# workshop4
---
Learn about Dictionary and start with Pandas

Hello,

### Outline

* What is Dictionary
  * Accessing values
  * Adding/ Removing new key-value pairs
  * Starting with values in a Dictionary
* How to work with Dictionary
  * Looping
    * Loop through all key-value pairs
    * Loop through all the keys in a Dictionary
    * Loop through all a Dictionary's keys in order
    * Loop through all values in a Dictionary
  * Nesting
    * A list of Dictionary
    * A list of a Dictionary
    * A Dictionary in a Dictionary

#### What is a Dictionary?

Let us take a simple to explain what Dictionary or `Dict` is

```python
"""
Example of a Dictionary with a variable named `python_class`.
"""
python_class = {"Name": ["Alice", "Bob", "Chris"], "Occupation": ["student", "marketer", "researcher"], "Age": [20, 27, 35]}

print(python_class)
```
##### How to access values
```python
print(python_class["student"])
print(python_class["student"][0])
```

```python
python_class.values() # Return an object Dictionary_values, e.g. dict_values([key1, key2])
```

```python
python_class.keys() # Return an object of Dictionary keys, e.g. dict_keys([key1, key2])
```

```python
python_class.items() # Return an object of Dictionary item, e.g. dict_items([(key1, value1), (key2, value2)])
```

** Why dict_items, dict_values, dict_values? **

##### How to add/ remove new key-value pairs
```python
python_class["Year of Experience"] = "Less than a year" #Add a value.
print(python_class)

del python_class["Year of Experience"] #Remove keys and values.
print(python_class)
```

#### How to work with Dictionary
```python
for key, value in python_class.items():
  print("\n Key %s" % key)
  print("\n Value %s" % value)
```


```python
class PyLadiesWorkshop:
    def __ini__(self):
        None
    def get_name(self):
        None
    def get_occupation(self):
        None
    def get_age(self):
        None
```
