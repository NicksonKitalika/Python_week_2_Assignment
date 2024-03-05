# Python List Operations

This repository contains a Python script demonstrating various operations on a list named `my_list`. The script includes operations such as appending, inserting, extending, removing, sorting, and finding the index of an element in the list.

## Code Overview

```python
# An empty list called my_list
my_list = []

# Appending elements to my_list
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Inserting the value 15 at the second position in my_list
my_list.insert(1, 15)

# Extending my_list with another list
my_list.extend([50, 60, 70])

# Removing the last element from my_list
my_list.pop()

# Sorting my_list in ascending order
my_list.sort()

# Finding the index of the value 30 in my_list
index_of_30 = my_list.index(30)
print("Index of 30: ", index_of_30)
