# Python OOP Project: Employee Management System

## About the Project
The **Employee Management System** is a beginner-friendly Python project created to practise Object-Oriented Programming (OOP) concepts. It allows users to create person records, employee records, and manager records, and display their details through a menu-driven interface.

## Features
- Create a Person with a name and age.
- Create an Employee with an ID, name, age, and salary.
- Create a Manager with employee details and a department.
- Display saved Person, Employee, and Manager details.
- Exit the program through the menu.
- Check class inheritance using Python's `issubclass()` function.

## OOP Concepts Used
- **Classes and Objects:** `Employee`, `Manager`, and `Developer` classes.
- **Constructor (`__init__`):** Initializes object attributes.
- **Encapsulation:** Uses private attributes such as `__employee_id` and `__salary`.
- **Getters and Setters:** Retrieve and update employee ID and salary.
- **Inheritance:** `Manager` and `Developer` inherit from `Employee`.
- **Method Overriding:** The `Manager` and `Developer` classes override the `display()` method.
- **`super()`:** Calls the parent class constructor and display method.
- **`issubclass()`:** Checks whether a class inherits from another class.
- **Menu-Driven Programming:** Uses a `while` loop and conditional statements to handle user choices.

## Technologies Used
- Python 3
- VS Code (recommended editor)

## How to Run the Project

1. Install Python 3 on your computer.
2. Save the source code in a file named `employee_management.py`.
3. Open the project folder in VS Code or a terminal.
4. Run the following command:

   ```bash
   python employee_management.py
   ```

5. Follow the menu displayed in the terminal.

## Menu Options

| Option | Operation |
|---|---|
| 1 | Create a Person |
| 2 | Create an Employee |
| 3 | Create a Manager |
| 4 | Show Details |
| 5 | Exit |

## Classes Overview

### 1. Employee
The parent class that stores employee ID, name, age, and salary. It also provides methods to access and display employee information.

### 2. Manager
A child class of `Employee` that adds a department attribute and extends the display functionality.

### 3. Developer
A child class of `Employee` that adds a programming language attribute and extends the display functionality.

## Current Limitations
- Only one Person, Employee, and Manager record can be stored at a time in the current program.
- Developer objects can be defined but cannot currently be created through the menu.
- Records are stored in memory and are not saved to a file or database.
- Invalid numeric inputs may cause the program to stop with an error.

## Future Improvements
- Add support for multiple employees and managers.
- Add a menu option to create Developer objects.
- Add input validation and error handling.
- Implement search, update, and delete operations.
- Save employee records to a file or database.

## Learning Objective
The main objective of this project is to understand and practise Python OOP concepts through a simple, interactive Employee Management System.

## Author
Created as a Python Object-Oriented Programming practice project.
