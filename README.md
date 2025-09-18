# database_final_project
# MySQL Membership Management System

This project is a **Membership Management System** built with MySQL. It manages **members**, their **dependents**, **entry fees**, and **monthly contributions** over multiple years. The system demonstrates relational database design, data normalization, and automated SQL generation using Python.

---

## Features

1. **Members Table**
   - Stores member details including first name, last name, phone, email, and location.
   
2. **Dependents Table**
   - Tracks dependents of each member along with their relationship (child, parent, spouse, etc.).
   
3. **Entry Fees Table**
   - Stores initial one-time entry fees paid by members with a payment date.
   
4. **Contributions Table**
   - Tracks monthly contribution payments from members.
   - Contributions vary by period:
     - Oct–Dec 2023: 3,000 TZS/month
     - Jan–Dec 2024: 5,000 TZS/month
     - Jan–Sep 2025: 10,000 TZS/month
   - Contributions are automatically generated using a Python script.

---

## Requirements

- MySQL 8.x or compatible version
- MySQL client (e.g., MySQL Workbench or command line)

---

## Installation & Setup

1. **Clone the repository:**
```bash
git clone https://github.com/msomea/database_final_project.git
cd mysql_membership_project
```

2. **Create the Database:**
- open membership_db using MySQL Workbench
- run the script to create database, tables and insert data into tables

3. **Project Structure**

mysql_membership_project/

        │

        ├── membership_db.sql       # Generated SQL for contributions (after running Python script)

        └── README.md

4. **License**

This project is for educational purposes for MySQL Database Management tutorials. Feel free to modify and use it for learning.

Author
_Raphael Msomea_
Email: _msomearaphael@gmail.com_
