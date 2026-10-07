# 👨‍💼 Employee Management System

A desktop-based **Employee Management System** built with **Python, Object-Oriented Programming (OOP), Tkinter, and SQLite**.

This project was created to simulate a real-world employee management application and apply Python programming and OOP concepts in a practical software project.

---

## 📌 Project Overview

The Employee Management System is a desktop application that allows users to manage employee information through a graphical user interface.

The system provides tools for adding, viewing, searching, updating, and deleting employee records, as well as managing salaries, bonuses, deductions, working hours, and overtime.

Employee data is stored in an **SQLite database**, allowing the information to remain available after closing and reopening the application.

---

## ✨ Features

- 👤 Add new employees
- 📋 View employee records
- 🔍 Search for employees
- ✏️ Update employee information
- 🗑️ Delete employee records
- 💰 Manage employee salaries
- 🎁 Calculate employee bonuses
- ➖ Apply salary deductions
- ⏱️ Track working hours
- ⏰ Calculate overtime
- 📊 Dashboard with employee statistics
- 💾 Store data using SQLite
- 🖥️ User-friendly Tkinter GUI

---

## 🧩 Employee Roles

The system includes different employee types:

### Employee
The base class that contains the common employee information and functionality.

### Manager
Inherits from the `Employee` class and provides manager-specific behavior, including a different bonus calculation.

### Developer
Inherits from the `Employee` class and provides developer-specific behavior.

This structure makes the application easier to extend with additional employee roles in the future.

---

## 🧠 OOP Concepts Applied

This project demonstrates the main Object-Oriented Programming concepts:

### 1. Encapsulation

Employee salary is protected using a private attribute:

```python
self.__salary

Salary operations are handled through methods such as:

get_salary()
change_salary()
deduct_salary()

This prevents direct access to the salary attribute.

2. Inheritance

Manager and Developer inherit from the base Employee class.

class Manager(Employee):
    pass

class Developer(Employee):
    pass

This allows the child classes to reuse common employee functionality.

3. Polymorphism

Different employee types can have different implementations of the same method.

For example, bonus calculations can vary depending on the employee's position.

This allows the system to treat different employee types through a common interface while still providing role-specific behavior.

4. Abstraction

The project separates different responsibilities such as:

Employee management
Salary operations
Database operations
GUI operations

This helps keep the application organized and easier to maintain.

🗄️ Database

The application uses SQLite for persistent data storage.

The employee table contains information such as:

Field	Description
ID	Unique employee identifier
Name	Employee name
Age	Employee age
Salary	Employee salary
Position	Employee job position

SQLite was chosen because it is lightweight, easy to integrate with Python, and does not require a separate database server.

💰 Salary Management

The system provides several salary-related operations.

Salary Changes

Employees can have their salary increased or modified.

Bonuses

Different employee roles can receive different bonus percentages.

For example:

Employee → 10%
Manager → 15%
Developer → 12%
Salary Deductions

The system also supports fixed salary deductions.

For example:

Salary: 15000
Deduction: 2000
Remaining Salary: 13000
⏱️ Working Hours & Overtime

The system includes working-hour functionality.

Employees can record their working hours, and overtime can be calculated when the employee works more than the standard working hours.

This feature was added to make the application closer to a real-world employee management system.

🖥️ Dashboard

The application includes a dashboard designed to provide a quick overview of the employee system.

The dashboard can display information such as:

Total employees
Different employee positions
Salary-related information
Employee statistics

The GUI was designed using Tkinter with a dashboard-style layout and sidebar navigation.

🛠️ Technologies Used
Technology	Purpose
Python	Main programming language
OOP	Application structure
Tkinter	Graphical User Interface
SQLite	Database
SQL	Database operations
📂 Project Structure
Employee-Management-System/
│
├── main.py
├── employee_management.db
├── README.md
└── assets/
    └── screenshots/

The structure may change depending on the final version of the project.

▶️ How to Run
1. Clone the repository
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
2. Open the project folder
cd Employee-Management-System
3. Run the application
python main.py

The application will automatically connect to the SQLite database.

📸 Screenshots

Screenshots of the application can be added here to demonstrate the GUI and dashboard.

Dashboard

Add dashboard screenshot here.

Employee Management

Add employee management screenshot here.

Employee Records

Add employee records screenshot here.

🎥 Demo

A demonstration video of the Employee Management System is available with the project.

The demo shows the main features of the application, including employee management, database operations, salary management, and the graphical interface.

🎯 Project Goals

The main goals of this project were:

Practice Python OOP in a real-world application.
Apply Encapsulation, Inheritance, Polymorphism, and Abstraction.
Build a desktop GUI using Tkinter.
Connect Python with an SQLite database.
Implement CRUD operations.
Practice organizing a multi-component Python application.
Build a practical project suitable for a software portfolio.
📚 What I Learned

While developing this project, I gained practical experience in:

Python Object-Oriented Programming
Classes and Objects
Encapsulation
Inheritance
Polymorphism
Abstraction
Tkinter GUI development
SQLite database integration
SQL and CRUD operations
Application structure and organization
Connecting a GUI with a database
Building a complete desktop application
🚀 Future Improvements

Possible future improvements include:

🔐 User authentication and login system
📅 Complete attendance system
🕐 Check-in / Check-out functionality
📈 More advanced dashboard analytics
📊 Generate employee reports
📁 Export employee data to Excel or CSV
🔎 Advanced filtering and searching
🎨 Further UI/UX improvements
👥 Additional employee roles
👨‍💻 Author

Ali Mohamed

This project is part of my journey in Python programming and software development.

I am continuously working on building practical projects and improving my programming and Machine Learning skills.

⭐ If you find this project useful, feel free to star the repository!

#Python #OOP #Tkinter #SQLite #PythonProject #DesktopApplication
