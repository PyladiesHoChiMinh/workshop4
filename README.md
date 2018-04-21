# workshop4
---
Learn about Dictionary and start with Pandas

Long time no see,

In this session, we will walk you through through a learning session of how to use dictionary and get started with `pandas`, one of the most popular open-source library in `python`.

Before jumping into content, we would like to thank Eric Matthews for his amazing book "Python Crash Course: A Hands-on, Project-based Introduction to Programming"
Again, feel free to ask if you have any question.

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
Example of a Dictionary with a variable named `workshop_attendee`.
"""
workshop_attendee = {"Name": ["Alice", "Bob", "Chris"], "Occupation": ["student", "marketer", "researcher"], "Age": [20, 27, 35]}

print(workshop_attendee)
```
In simple words, we would say `Dict` is a data structure allowing us to
##### How to access values
```python
print(workshop_attendee["student"])
print(workshop_attendee["student"][0])
```

```python
# Return an object Dictionary_values, e.g. dict_values([key1, key2])
workshop_attendee.values()
```

```python
# Return an object of Dictionary keys, e.g. dict_keys([key1, key2])
workshop_attendee.keys()
```

```python
# Return an object of Dictionary item, e.g. dict_items([(key1, value1), (key2, value2)])
workshop_attendee.items()
```

** Why dict_items, dict_values, dict_values? **

##### How to add/ remove new key-value pairs
```python
workshop_attendee["Year of Experience"] = "Less than a year" #Add a value.
print(workshop_attendee)

del workshop_attendee["Year of Experience"] #Remove keys and values.
print(workshop_attendee)
```

#### How to work with Dictionary
```python
for key, value in workshop_attendee.items():
  print("\n Key %s" % key)
  print("\n Value %s" % value)
```
