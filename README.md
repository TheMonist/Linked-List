# Linked-List

This is an implementation of a linked list in javascript. A linked list is a dyanamic data structure, that is a "linear" collection of data elements called nodes. Each node holds a single element of data. These nodes also "point" to the next node in the list by way of a pointer. It is like an array in javascript, however the main difference is that a node can be inserted or removed without reallocating any other elements. This is to say that linked lists are not limited to a certain size and the order of elements in the list is not dependent on where it is in memory.

## Features

This implementation has the following functions and patterns:

### Factories/Classes:

1. `LinkedList` class / factory, which will represent the full list.
2. `Node` class / factory, containing a value property and a link to the nextNode, set both as null by default.

### Functions:

1. `append(value)`: Adds a new node containing value to the end of the list
2. `prepend(value)`: Adds a new node containing value to the start of the list
3. `size`: Returns the total number of nodes in the list
4. `head`: Returns the first node in the list
5. `tail`: Returns the last node in the list
6. `at(index)`: Returns the node at the given index
7. `pop`: Removes the last element from the list
8. `contains(value)`: Returns true if the passed in value is in the list and otherwise returns false.
9. `find(value)`: Returns the index of the node containing value, or null if not found.
10. `toString`: Represents your LinkedList objects as strings, so you can print them out and preview them in the console. The format should be: `[ value ] -> [ value ] -> [ value ] -> null`
11. `insertAt(value, index)`: That inserts a new node with the provided value at the given index.
12. `removeAt(index)`: That removes the node at the given index.
