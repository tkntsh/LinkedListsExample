# LinkedList Example in Java

This project demonstrates a simple implementation of a singly linked list in Java. The program includes functionality to add nodes to the linked list and print its contents.

Features

- **Node Structure**: Each node stores an integer value and a reference to the next node in the list.
- **Linked List Operations**:
  - Append new nodes to the end of the list.
  - Print the entire linked list to the console.

## Code Structure

### `Node` Class

Represents a single node in the linked list. Each node contains:
- An integer `data` field to store the value.
- A `next` field that points to the next node in the list.

### `LinkedList` Class

Implements the singly linked list. Key methods include:
- **`append(int data)`**: Adds a new node with the given data to the end of the list.
- **`printList()`**: Traverses the linked list and prints all the nodes in order.

### `main` Method

Demonstrates the functionality of the linked list:
1. Creates a linked list.
2. Adds nodes with values `10`, `20`, and `30`.
3. Prints the linked list.

## Usage

### Prerequisites

- Java Development Kit (JDK) installed on your system.

### Compilation and Execution

1. Compile the `LinkedList.java` file:
   ```bash
   javac LinkedList.java
