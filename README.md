# 📝 Assignment: Data Manipulation and Transactions

## 📌 Overview
This project demonstrates the use of **basic SQL statements** for database creation and manipulation.  
It focuses on creating tables, inserting records, and updating data using SQL queries.

The assignment is designed to give hands-on practice with **Data Manipulation Language (DML)** and simple **transaction-related operations** in SQL.

---

## 🎯 Learning Objectives
- ➕ Create tables and define the structure of a database.
- ✍️ Insert records into a table.
- 🔄 Update records in a table.
- 💻 Practice SQL operations that form the foundation of database management.

---

## 📋 Files in This Project
- `answers.sql` → Contains all SQL queries for the assignment.
- `README.md` → Documentation and overview of the assignment.

---

## 🚀 How to Run the Queries
1. Open **MySQL Workbench** (or any SQL database environment).
2. Create a new database (optional):
   ```sql
   CREATE DATABASE school;
   USE school;
Copy and paste the queries from answers.sql into your SQL editor.

Run each query step by step to:

Create the student table.

Insert 3 student records.

Update the age of a student with id = 2.

🧑‍💻 Example Workflow
sql
Copy
Edit
-- Create the table
CREATE TABLE student (
    id INT PRIMARY KEY,
    fullName VARCHAR(100),
    age INT
);

-- Insert records
INSERT INTO student (id, fullName, age)
VALUES (1, 'Alice Johnson', 19),
       (2, 'Brian Smith', 18),
       (3, 'Catherine Lee', 21);

-- Update a record
UPDATE student
SET age = 20
WHERE id = 2;
📌 Notes
Ensure the database is selected before running the queries.

If you re-run the script multiple times, you may need to drop the table first:

sql
Copy
Edit
DROP TABLE IF EXISTS student;
👤 Author & License
Author: [Ukwuoma Harrison Chiedoziem]

License: Free to use for educational purposes.
