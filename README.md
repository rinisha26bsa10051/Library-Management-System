# Library Management System

A simple **Library Management System** developed using Python as an academic project. The program provides a menu-driven interface for performing basic library operations such as adding, issuing, returning, and viewing books.

##  Project Overview

The Library Management System is a console-based Python application designed to demonstrate fundamental programming concepts through a practical use case.

The system maintains a collection of books and allows the user to perform four primary operations:

1. **Add Books**
2. **Issue Books**
3. **Return Books**
4. **View Books**

The program continues running until the user selects the **Exit** option.

##  Features

### 1. Add Books

Allows the user to add a new book to the library.

### 2. Issue Books

Allows the user to issue a book if it is currently available in the library. Once issued, the book is removed from the available books list.

### 3. Return Books

Allows the user to return a book to the library. The returned book is added back to the collection.

### 4. View Books

Displays all currently available books along with their serial numbers.

### 5. Exit

Terminates the program when the user selects the exit option.

##  Technologies Used

* **Programming Language:** Python
* **Platform:** Google Colab / Python
* **Interface:** Command-Line Interface (CLI)

##  Python Concepts Demonstrated

This project demonstrates several fundamental Python programming concepts:

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
* Basic program control using `break`
* Menu-driven programming

## ⚙️ How the Program Works

The program uses a Python list named `library` to store the names of currently available books.

```python
library = []
```

The system then uses separate functions for each major operation:

```text
                 
##  How to Run

### Option 1: Google Colab

1. Open the Python notebook in Google Colab.
2. Run the code cell.
3. Select an option from the displayed menu.
4. Follow the instructions provided by the program.

### Option 2: Run Locally

Make sure Python is installed on your computer.

Save the program as:

```text
library_management.py
```

Then run:

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

The current version stores book information using a Python **list**.

```python
library = []
```

This means that the data exists only while the program is running. Once the program is terminated, the stored book information is lost.

No external database or file storage is used in this version.

##  Learning Objective

The primary objective of this project is to apply fundamental Python programming concepts to develop a simple real-world application.

Through this project, concepts such as **functions, lists, loops, conditional statements, user input, and menu-driven programming** are combined to create a functional Library Management System.

#  Author

Rinisha Bhowmik

B.Tech CSE (Cloud Computing and Automation)
Reg no: 26BSA10051
