# Student-Record-Management-System
A desktop-based Student Record Management System developed using Python (Tkinter) and MySQL. The application implements full CRUD functionality with a user-friendly GUI, enabling efficient management of student data.

# 📚 Student Record Management System

## 📌 Overview
The Student Record Management System is a desktop-based application built using Python's Tkinter library and MySQL database. 
It provides a user-friendly graphical interface to manage student records efficiently.

This project is suitable for beginners learning GUI development and database integration in Python.

## 🚀 Features

- ➕ Add new student records
- 🔍 Search student records by Roll No, Name, or Subject
- ✏️ Update existing student details
- 📋 Display all student records in a table
- ❌ Delete student records
- 🖥️ Interactive and simple GUI using Tkinter

## 🛠️ Technologies Used

- Python (Core Programming)
- Tkinter (GUI Development)
- MySQL (Database)
- PyMySQL (Database Connector)

## 📂 Project Structure

Student-Record-System/
│
├── main.py              # Main application file
├── README.md            # Project documentation
└── requirements.txt     # Dependencies

## ⚙️ Installation Guide

### Step 1: Clone Repository
git clone https://github.com/your-username/student-record-system.git
cd student-record-system

### Step 2: Install Required Libraries
pip install pymysql

### Step 3: Setup MySQL Database

Open MySQL Command Line or Workbench and execute:

CREATE DATABASE pymysql;

USE pymysql;

CREATE TABLE student (
    rollNo INT PRIMARY KEY,
    name VARCHAR(50),
    fname VARCHAR(50),
    sub VARCHAR(50),
    grade VARCHAR(10)
);

### Step 4: Configure Database in Code

Update your database credentials in the Python file:

pymysql.connect(
    host="localhost",
    user="root",
    passwd="your_password",
    database="pymysql"
)

### Step 5: Run Application

python main.py

## 🧠 How It Works

- The application uses Tkinter to create GUI components like buttons, forms, and tables.
- PyMySQL connects Python to the MySQL database.
- CRUD operations (Create, Read, Update, Delete) are performed using SQL queries.
- Data is displayed using the Treeview widget.

## 📸 Output Preview


![alt text](<Screenshot 2026-03-23 195440.png>)







