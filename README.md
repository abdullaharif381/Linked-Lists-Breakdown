# Linked List Breakdown

This C++ program demonstrates the breakdown of a linked list into sublists of a specified size (k). It uses a templated linked list class to create and manipulate linked lists.

## Overview

This project includes a C++ program that breaks down a linked list into smaller sublists, each containing a maximum of k elements. It uses a templated linked list class to manage the data and provides a user-friendly interface for input and display.

## Table of Contents

- [Introduction](#introduction)
- [Classes and Functions](#classes-and-functions)
  - [LinkedList Class](#linkedlist-class)
  - [BreakDown Function](#breakdown-function)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This program is designed to showcase the breakdown of a linked list into sublists, which can be useful in various data processing scenarios. It allows you to create a linked list, specify the sublist size (k), and then breaks down the list accordingly.

## Classes and Functions

### LinkedList Class

The `LinkedList` class represents a templated linked list with the following functionalities:

- `addNode(T val)`: Adds a new node with the given value to the end of the list.
- `friend ostream& operator<<(ostream& os, const LinkedList<T>& list)`: Overloads the `<<` operator to display the contents of the linked list.

### BreakDown Function

The `BreakDown` function takes an input linked list and an integer `k` as parameters. It breaks down the input linked list into sublists, each containing a maximum of `k` elements. The result is returned as a new linked list of linked lists.

## Getting Started

1. Clone this repository to your local machine.
2. Compile the `main.cpp` file using a C++ compiler.
