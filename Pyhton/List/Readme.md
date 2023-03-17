# Lists

Lists are used to store multiple items in a single variable.

Lists are one of 4 built-in data types in Python used to store collections of data, the other 3 are Tuple, Set, and Dictionary, all with different qualities and usage.

Lists are created using square brackets. 

```python
list = ["apple", "banana", "orange", "strawberry"]
print("The list is: ", list)
```

## List Items

List items are ordered, changeable, and allow duplicate values.

List items are indexed, the first item has index [0], the second item has index [1] etc.

## Ordered

When we say that lists are ordered, it means that the items have a defined order, and that order will not change.

If you add new items to a list, the new items will be placed at the end of the list.

```python
list = ["apple", "banana", "orange", "strawberry"]
print("The list is: ", list)
print("List item 1", list[0])

```

## Changeable

The list is changeable, meaning that we can change, add, and remove items in a list after it has been created.

## Allow Duplicates

Since lists are indexed, lists can have items with the same value.

```python
list = ["apple", "banana", "orange", "strawberry", "apple"]
print("The list is: ", list)
```

## Access Items

List items are indexed and you can access them by referring to the index number.

```python
list = ["apple", "banana", "orange", "strawberry", "apple"]
print("The list is: ", list[0])
print("The list is: ", list[1])
```


Source(https://www.w3schools.com/python/python_lists.asp)
