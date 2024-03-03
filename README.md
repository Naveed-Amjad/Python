# Data Structures and Algorithms in Python

This repository contains Python implementations of various data structures and algorithms.

## Introduction

- Data structures and algorithms are fundamental concepts in computer science and are essential for solving complex problems efficiently. This repository aims to provide Python implementations of commonly used data structures 
- and algorithms, along with explanations and examples.

## Data Structures

The following data structures are implemented in this repository:

- Stack
- Queue

# PS: I will upload other data strcurues and algorithms notebooks as well

Each data structure is implemented as a Python class with methods for common operations.

## Algorithms

- I will upload algorithms notebooks as well

## Usage

To use the data structures and algorithms in your Python projects, you can clone this repository or download the specific Python files you need. Then, import the classes or functions into your Python code and use them as required.

# Stack data structure
Example usage:

# Create a stack
stack = Stack()

# Push elements onto the stack
- stack.push(10)
- stack.push(20)
- stack.push(30)

# Pop elements from the stack
print(stack.pop())  # Output: 30
print(stack.pop())  # Output: 20

# Queue data structure
Example usage:

# Create a queue
queue = Queue()

# Enqueue elements into the queue
- queue.enqueue(10)
- queue.enqueue(20)
- queue.enqueue(30)

# Dequeue elements from the queue
print(queue.dequeue())  # Output: 10
print(queue.dequeue())  # Output: 20

# Linked List Implementation in Python

This repository contains a Python implementation of a singly linked list. A linked list is a linear data structure consisting of a sequence of elements called nodes. Each node stores a reference (link) to the next node in the sequence.

## Overview

This Python implementation provides a LinkedList class that allows you to perform various operations on a singly linked list, such as inserting elements at the start or end, deleting elements from the start, end, or a specific location, finding the length of the list, and displaying the elements of the list.

## Features

- Insertion of elements at the start and end of the list
- Insertion of elements at a specific location in the list
- Deletion of elements from the start, end, or a specific location in the list
- Calculation of the length of the list
- Displaying the elements of the list

## Usage

To use the LinkedList class in your Python projects, you can clone this repository or download the `linked_list.py` file. Then, import the LinkedList class into your Python code and create LinkedList objects to perform various operations on linked lists.

Example usage:

# Create a linked list
list = LinkedList()

# Insert elements at the end of the list
- list.insertAtEnd(1)
- list.insertAtEnd(2)
- list.insertAtEnd(3)

# Display the elements of the list
list.display()

# Find the length of the list
print("Length of list =", list.findLength())

# Delete an element from a specific location in the list
list.deleteFromLocation(2)

# Display the modified list
list.display()
