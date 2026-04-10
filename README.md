# student-grades-sql-project


Developed a SQL-based student grades management project to store student details and academic performance records. Implemented joins, filtering, sorting, grouping, and aggregate queries to analyze CGPA and final grades across different grade levels.


It includes:
- Database creation
- Table creation
- Data insertion
- SQL queries for analysis
- Joins between tables
- Filtering, sorting, grouping, and aggregate functions

## Project Overview

The project creates a database named `student_grades_db` with two tables:

1. **students**
   - Stores student personal and academic details
   - Includes fields like student name, grade level, CGPA, lunch status, birthday, and email

2. **student_grades**
   - Stores semester-wise class grade records
   - Includes semester ID, class ID, department, class name, student ID, and final grade

This project helps in understanding how relational databases work using SQL.

## Features

- Create a database and tables
- Insert sample student records
- Insert student grade records
- Use `INNER JOIN` and `LEFT JOIN`
- Filter students based on lunch and CGPA
- Sort students by CGPA
- Calculate average CGPA by grade level
- Use `GROUP BY` and `HAVING`
- Display final grades of students

## SQL Concepts Used

- `CREATE DATABASE`
- `USE`
- `CREATE TABLE`
- `INSERT INTO`
- `SELECT`
- `INNER JOIN`
- `LEFT JOIN`
- `WHERE`
- `ORDER BY`
- `GROUP BY`
- `HAVING`
- `AVG()`

## Sample Queries Included

Some of the queries in this project:
- Display all student records
- Join student details with grades
- Show student name, CGPA, and lunch status
- Find students who had school lunch and CGPA greater than 3.0
- Sort students by CGPA in descending order
- Calculate average CGPA for each grade level
- Show grade levels with average CGPA below 3.3
- Show final grades for each student

## Learning Outcome

By working on this project, I practiced:
- Database design
- Writing basic and intermediate SQL queries
- Working with relationships between tables
- Using aggregate functions for analysis
- Organizing academic data in a structured way

## Tools Used

- MySQL
- MySQL Workbench / SQL editor

## How to Run

1. Open MySQL Workbench or any SQL editor
2. Copy the SQL script into a new query tab
3. Run the script step by step or all at once
4. Use the `student_grades_db` database
5. Execute the SELECT queries to view results

## Note

This project is created for learning and practice purposes.

## Author

**Pratik Inkar**
