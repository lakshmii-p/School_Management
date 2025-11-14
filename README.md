
School Management System

A complete school administration software built with Python, PyQt6, Qt Designer, and MySQL.

A fully functional CRUD-based desktop application designed to manage student registration, marks, attendance, fees, and administrative reports.

<br>
✨ Features
<br>
🔐 Login System

Secure admin login

Error message for invalid credentials

Logout functionality

<br>
🧑‍🎓 Student Management

Add, edit, and delete student details

Auto-increment registration number

Automatically calculate age from Date of Birth

Stores personal and academic information

<br>
📝 Marks Management

Add, edit, and delete marks

Fetch all student registration numbers

Retrieve marks for selected exams

Clean marks entry interface

<br>
📆 Attendance Management

Add, edit, and delete attendance

Auto-fill current date

Fetch attendance by specific date

Simple attendance tracking UI

<br>
💰 Fees Management

Add, edit, and delete fee details

Auto-fill current date & month

Fetch fee information using receipt number

Print preview and print receipt support

<br>
📊 Reports Dashboard

Student Report

Marks Report

Attendance Report

Fees Report

All reports organized in one place

<br>
🛠️ Tech Stack

Python 3

PyQt6

Qt Designer

MySQL

XAMPP

<br>
📥 Installation Guide
1. Clone the Repository
git clone https://github.com/lakshmii-p/School_Management.git

<br>
2. (Optional) Create a Virtual Environment
python -m venv env
env\Scripts\activate

<br>
3. Install Requirements
pip install -r requirements.txt

<br>
4. Set Up MySQL Database

Install XAMPP

Copy the school_db folder to:

C:\xampp\mysql\data\school_db


OR create a symbolic link (Run CMD as Administrator):

mklink /d C:\xampp\mysql\data\school_db "C:\path\to\project\school_db"

<br>
5. Start MySQL (via XAMPP)
<br>
6. Run the Application
cd School_Management
python ./main.py

<br>
📘 Usage

Register students

Manage marks and attendance

Handle fee payments

Generate printable receipts

View admin-level reports

<br>
💡 Why This Project Stands Out

Complete end-to-end school management application

Clean and intuitive PyQt6 user interface

Real-world CRUD operations

Strong database integration

Great project for resumes, internships, and placements

<br>
🙏 Acknowledgments

Thanks to Python, PyQt6, Qt Designer, and MySQL for enabling this project.

<br>
