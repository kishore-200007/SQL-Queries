# SQL Employee Database Practice

A beginner-friendly SQL project that demonstrates basic SQL operations using an **Employee** table. This repository contains the SQL script to create the table, insert sample data, and practice common SQL queries.

## Project Overview

This project is designed for students and beginners who want to learn SQL fundamentals through practical examples.

The project includes:
- Database creation
- Table creation
- Sample employee data
- 20 SQL practice queries


## Technologies Used

- SQL
- MySQL Workbench (or any SQL database)


## Database Structure

## Table: Employee

| Column | Data Type |
|---------|-----------|
| EmpID | INT (Primary Key) |
| Name | VARCHAR(50) |
| Department | VARCHAR(50) |
| Salary | INT |
| Age | INT |
| City | VARCHAR(50) |


## Sample Data

| EmpID | Name | Department | Salary | Age | City |
|------:|-------|------------|-------:|----:|------------|
|101|Rahul|IT|60000|25|Chennai|
|102|Priya|HR|45000|28|Coimbatore|
|103|Arun|IT|70000|30|Madurai|
|104|Sneha|Finance|55000|27|Chennai|
|105|Karthik|IT|80000|35|Salem|
|106|Divya|HR|50000|24|Erode|
|107|Vijay|Finance|65000|32|Trichy|
|108|Anitha|Marketing|48000|26|Chennai|


## SQL Topics Covered

- SELECT
- WHERE
- DISTINCT
- ORDER BY
- LIKE
- BETWEEN
- IN
- AND
- OR
- NOT
- LIMIT / TOP
- Comparison Operators


## Practice Queries

1. Display all employee records.
2. Display only Name and Salary.
3. Display unique departments.
4. Find employees whose salary is greater than 60000.
5. Find employees from Chennai.
6. Find employees whose age is greater than or equal to 30.
7. Display employees who belong to the IT department.
8. Find employees whose salary is between 50000 and 70000.
9. Find employees from Chennai or Madurai.
10. Find employees not working in HR.
11. Sort employees by salary in ascending order.
12. Sort employees by salary in descending order.
13. Display the top 3 highest-paid employees.
14. Display employee names in alphabetical order.
15. Display employees whose names start with 'A'.
16. Display employees whose names end with 'a'.
17. Display employees whose names contain 'ar'.
18. Display employees whose age is not between 25 and 30.
19. Display employees from the IT department whose salary is greater than 65000.
20. Display all employees ordered by Department and Salary (highest first).


##  How to Run

1. Open MySQL Workbench (or any SQL IDE).
2. Create a new database.

_sql_
CREATE DATABASE company;
USE company;


3. Create the Employee table.
4. Insert the sample data.
5. Execute the SQL queries one by one.
6. Observe the output.


## Learning Outcomes

After completing this project, you will understand:

- Creating databases and tables
- Inserting records
- Retrieving data using SELECT
- Filtering records using WHERE
- Sorting results using ORDER BY
- Using LIKE, BETWEEN, IN, and DISTINCT
- Writing beginner-level SQL queries


## Author

**Kishore P**

