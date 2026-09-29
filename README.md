# Library Management System

## Project Overview

The Library Management System is a simple console-based application developed using Python. It is designed to perform basic library operations through a menu-driven interface.

The system allows users to add books, issue books, return books, and view the books currently available in the library.

## Features

The application provides the following functionalities:

### 1. Add Books

Allows the user to add a book to the library collection.

### 2. Issue Books

Allows the user to issue a book if it is currently available in the library. Once issued, the book is removed from the available books list.

### 3. Return Books

Allows the user to return a book to the library. The returned book is added back to the collection.

### 4. View Books

Displays the list of books currently available in the library along with their serial numbers.

### 5. Exit

Terminates the program when the user selects the exit option.

## Technologies Used

* Python
* Google Colab / Python
* Command-Line Interface (CLI)

## Python Concepts Demonstrated

This project demonstrates the following fundamental Python concepts:

* Variables
* Lists
* Functions
* Conditional statements (`if`, `elif`, `else`)
* `while` loops
* `for` loops
* User input using `input()`
* List methods such as `append()` and `remove()`
* Membership operators (`in`)
* Formatted strings (f-strings)
* `break` statement
* Menu-driven programming

## Program Structure

The program uses a Python list named `library` to store the books currently available.

```python
library = []
```

The application is divided into four main functions:

* `add_books()` — Adds a new book to the library.
* `issue_books()` — Issues an available book.
* `return_books()` — Adds a returned book to the library.
* `view_books()` — Displays the available books.

A continuous `while` loop provides the main menu and allows the user to perform multiple operations until the Exit option is selected.

## How to Run

### Using Google Colab

1. Open the project notebook in Google Colab.
2. Run the code cell.
3. Select an option from the menu.
4. Follow the instructions displayed by the program.

### Running Locally

Ensure that Python is installed on your system.

Save the program as:

```text
library_management.py
```

Run the program using:

```bash
python library_management.py
```

## Sample Menu

```text
-----Library Management System-----
1. Add Books
2. Issue Books
3. Return Books
4. View Books
5. Exit

Enter your choice:
```

## Data Storage

The current version uses a Python list to store the available books.

```python
library = []
```

The data is stored only in the program's memory during execution. Therefore, the book information is not permanently saved and will be lost when the program is terminated.

The current implementation does not use file storage or a database.

## Limitations

The current version is intended as a basic implementation for demonstrating fundamental Python concepts. Some limitations include:

* Book information is not stored permanently.
* There are no unique IDs for books.
* The system does not maintain information about library members.
* There is no due-date or fine management.
* Input validation is limited.
* The system does not distinguish between multiple copies of the same book.

## Future Improvements

The project can be further enhanced by implementing:

* File-based or database storage
* Unique identification numbers for books
* Library member management
* Book search functionality
* Book availability tracking
* Due dates and fine calculation
* Improved input validation
* Object-oriented programming using classes
* Graphical User Interface (GUI)
* Database integration using SQLite or another database system

## Learning Objective

The objective of this project is to apply fundamental Python programming concepts to a simple real-world application.

The project demonstrates how functions, lists, loops, conditional statements, user input, and menu-driven programming can be combined to create a functional Library Management System.

## Author

Rinisha Bhowmik

B.Tech CSE (Cloud Computing and Automation)
Reg no: 26BSA10051
