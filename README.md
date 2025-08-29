# Python Built-in Data Structures Assignment

## Overview
This Python script demonstrates various fundamental list operations including creating, modifying, and manipulating lists. It serves as an educational example of how to work with lists in Python.

## Operations Performed

1. **List Creation**: Initializes an empty list
2. **Appending Elements**: Adds multiple elements to the end of the list
3. **Inserting Elements**: Places an element at a specific position
4. **Extending Lists**: Combines another list with the existing one
5. **Removing Elements**: Deletes the last element from the list
6. **Sorting**: Arranges elements in ascending order
7. **Index Finding**: Locates the position of a specific value

## Code Explanation

```python
# Create an empty list called my_list
my_list = []

# Append elements: 10, 20, 30, 40
my_list.append(10)
my_list.append(20)
my_list.append(30)
my_list.append(40)

# Insert value 15 at the second position (index 1)
my_list.insert(1, 15)

# Extend with another list: [50, 60, 70]
my_list.extend([50, 60, 70])

# Remove the last element
my_list.pop()

# Sort in ascending order
my_list.sort()

# Find and print the index of value 30
index_of_30 = my_list.index(30)
print("Index of 30:", index_of_30)
```

## Expected Output
```
Index of 30: 3
Final my_list: [10, 15, 20, 30, 40, 50, 60]
```

## Key Concepts Demonstrated

- **List Methods**: `append()`, `insert()`, `extend()`, `pop()`, `sort()`, `index()`
- **Indexing**: Understanding zero-based indexing in Python lists
- **List Modification**: How lists can be dynamically changed after creation
- **Sorting**: Arranging elements in ascending order

## Usage

1. Run the script to see the list operations in action
2. Modify the values to experiment with different scenarios
3. Use as a reference for basic list manipulation techniques in Python

## Requirements

- Python 3.x

No external libraries are required for this script.
