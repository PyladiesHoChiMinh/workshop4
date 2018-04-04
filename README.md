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

python_class = {"Name": ["Alice", "Bob", "Chris"]; "occupation": ["student", "marketer", "researcher"]; "Age": [20, 27, 35]}

print(python_class)
```

```python
print(python_class["student"])
print(python_class["student"][0])
```

```python
python_class["Year of Experience"] = "Less than a year"
print(python_class)
```

```python
del python_class["Year of Experience"]
print(python_class)
```

```python
for key, value in python_class.items():
  print("\n Key" + key)
  print("\n Value" + value)
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
