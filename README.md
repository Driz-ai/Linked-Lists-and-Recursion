# Linked Lists and Recursion Lab

## Overview

This project demonstrates the implementation of a singly linked list using Python and recursive algorithms. The lab focuses on understanding node-based data structures while applying recursion to perform common linked list operations such as summing values, searching for data, and reversing the list.

## Learning Objectives

By completing this lab, you will be able to:

* Implement a singly linked list using Python classes.
* Create and link nodes dynamically.
* Insert nodes at the front and end of a linked list.
* Use recursion to:

  * Calculate the sum of all node values.
  * Search for a specific value.
  * Reverse a linked list in place.
* Write and run unit tests to verify functionality.
* Use Git and GitHub to manage feature branches and pull requests.

## Project Structure

```text
.
├── linked_list.py        # Node and LinkedList class implementations
├── test_linked_list.py   # Unit tests
├── main.py               # Optional manual testing script
└── README.md
```

## Features

### Linked List Operations

* `insert_at_front(data)` – Inserts a new node at the beginning of the list (O(1)).
* `insert_at_end(data)` – Inserts a new node at the end of the list (O(n)).

### Recursive Operations

* `recursive_sum()` – Returns the sum of all node values.
* `recursive_search(target)` – Returns `True` if the target value exists in the list; otherwise returns `False`.
* `recursive_reverse()` – Reverses the linked list in place using recursion.

### Utility

* `display()` – Prints the contents of the linked list.

## How to Run

1. Clone the repository:

```bash
git clone <your-repository-url>
```

2. Navigate into the project directory:

```bash
cd Linked-Lists-and-Recursion
```

3. Run the example program (optional):

```bash
python main.py
```

## Running the Tests

Execute the unit tests with:

```bash
python -m unittest
```

or

```bash
python -m unittest test_linked_list.py
```

If everything is implemented correctly, all tests should pass successfully.

## Example Output

```text
Original List:
30 -> 20 -> 10 -> 5

Sum: 65

Search 20: True
Search 100: False

Reversed List:
5 -> 10 -> 20 -> 30
```

## Technologies Used

* Python 3
* unittest
* Git
* GitHub

## Author

Developed as part of the Linked Lists and Recursion Lab.
