# 🎓 Student Management System (Python + Tkinter + MySQL)

A **Student Management System** developed using **Python Tkinter for GUI** and **MySQL for database management**.
This application allows users to **add, update, delete, search, and manage student records** efficiently through a simple graphical interface.

---

## 🚀 Features

* ➕ Add new student records
* ✏️ Update existing student details
* ❌ Delete student records
* 🔍 Search students by Roll Number, Name, or Contact
* 📋 Display all student data in a table
* 🧹 Clear form fields instantly
* 🗄️ Data stored permanently in MySQL database

---

## 🛠️ Technologies Used

* **Python 3**
* **Tkinter (GUI Library)**
* **MySQL Database**
* **PyMySQL Connector**

---

## 📂 Project Structure

```
Student-Management-System
│
├── student.py        # Main application file
├── database.sql      # Database structure
├── requirements.txt  # Required Python libraries
└── README.md         # Project documentation
```

---

## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```
https://github.com/akash7543/student-management-syste
```

### 2️⃣ Install Required Library

```
pip install pymysql
```

### 3️⃣ Setup MySQL Database

Create a database and table using the following SQL:

```
CREATE DATABASE stm;

USE stm;

CREATE TABLE students(
roll_no INT PRIMARY KEY,
name VARCHAR(50),
email VARCHAR(50),
gender VARCHAR(10),
contact VARCHAR(20),
dob VARCHAR(20),
address VARCHAR(100)
);
```
<img width="1345" height="635" alt="image" src="https://github.com/user-attachments/assets/9bef103e-0aa4-47c9-9778-ca9942d5907b" />


### 4️⃣ Run the Project

```
python student.py
```

---

## 🖥️ Application Interface

<img width="1345" height="680" alt="image" src="https://github.com/user-attachments/assets/81db1c1b-30f7-41b6-ac3d-40e9ca6a6815" />


The application includes:

* Student data entry form
* Student records table
* Search functionality
* CRUD operations

---

## 📸 Screenshot

*(Add your project screenshot here)*

---

## 🎯 Learning Objectives

This project demonstrates:

* GUI development using **Tkinter**
* Database connectivity using **PyMySQL**
* Performing **CRUD operations**
* Building real-world **desktop applications with Python**

---

## 👨‍💻 Author

**Akash Kumar Soni**
BCA (Data Science) Student
SRM Institute of Science & Technology

---

## ⭐ Support

If you like this project, consider giving it a **star ⭐ on GitHub**.
