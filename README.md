# MySQL-Assignment-SQL-DML-Queries-and-Joins
SQL assignment using MySQL to practise DML operations, filtering, sorting, aggregate functions, GROUP BY, HAVING, and INNER, LEFT, and RIGHT JOINs.
MySQL DML Queries, Aggregate Functions & Joins

📌 Overview

This repository contains my second SQL assignment completed as part of my Data Analytics learning journey.

The project uses a sample Employee Database to practise SQL queries, retrieve meaningful information, perform data filtering and sorting, calculate aggregate values, group records, and combine data from multiple tables using joins.

🗄️ Database Information

Database Name: employee

Tables Used

departments – Stores department IDs and department names.

location – Stores location IDs and location names.

employees – Stores employee details, including names, gender, age, hire date, designation, department, location, and salary.

📚 Topics Covered

1. Data Manipulation Language (DML)

INSERT INTO – Insert records into tables.

UPDATE – Modify existing records.

2. Filtering and Column Aliases

DISTINCT – Retrieve unique salary values.

AS – Assign aliases to columns.

WHERE – Filter records based on conditions.

AND – Combine multiple filtering conditions.

IS NULL – Identify missing values.

3. Sorting and Limiting Results

ORDER BY ASC – Sort records in ascending order.

ORDER BY DESC – Sort records in descending order.

LIMIT – Restrict the number of returned rows.

4. Aggregate Functions

SUM() – Calculate the total salary of employees in the Finance department.

MIN() – Find the minimum employee age.

MAX() – Find the maximum salary for each location.

AVG() – Calculate average salaries by designation.

COUNT() – Count employees in each department.

5. Grouping and Filtering Groups

GROUP BY – Group records by department, location, or designation.

HAVING – Filter grouped results based on aggregate conditions.

LIKE – Find designations containing the word 'Analyst'.

6. SQL Joins

INNER JOIN – Retrieve employee names, designations, and department names.

LEFT JOIN – List all departments and their employee counts, including departments without employees.

RIGHT JOIN – Display all locations and their assigned employees, including locations without employees.

📝 Assignment Tasks

The assignment includes queries to:

Retrieve distinct employee salaries.

Display employee ages and salaries using column aliases.

Find employees earning more than ₹50,000 who were hired before 1 January 2016.

Identify employees with missing designations and update the missing values.

Sort employees by department ID and salary.

Display the first five employees hired during 2018.

Calculate the total Finance department salary and minimum employee age.

Find maximum salaries by location.

Calculate average salaries for designations containing 'Analyst'.

Identify departments with fewer than three employees.

Find locations where female employees have an average age below 30.

Retrieve employee and department information using INNER JOIN.

Count employees in every department using LEFT JOIN.

List locations and their employees using RIGHT JOIN.

🛠️ Tools & Technologies

MySQL

MySQL Workbench

SQL

📂 Repository Structure

sql-dml-queries-and-joins/
│
├── README.md
├── Employee_Data.sql
└── DML_Queries.sql

README.md – Project overview, topics, and learning objectives.

Employee_Data.sql – SQL statements to populate the database with sample records.

DML_Queries.sql – SQL queries written to complete the assignment.

🎯 Learning Objectives

Through this assignment, I practised:

Retrieving and filtering data using SQL.

Updating missing values in a database.

Sorting and limiting query results.

Using aggregate functions for data analysis.

Grouping records and filtering aggregated results.

Joining relational tables.

Understanding the relationships between employees, departments, and locations.

Writing readable and structured SQL queries.
