# CODTECH-JOIN-TASK

Name:Sirisha Matsa

Company: CODTECH IT SOLUTIONS

ID: CT08DQC

Domain: SQL 

Duration: DEC-2024 TO JAN-2025

Mantor: NEELA SANTOSH KUMAR

# OVERVIEW OF THE PROJECT:

***PROJECT: JOINS***

# OBJECTIVE:

The SQL queries integrate data from EMP and DEPT tables using various joins (INNER, LEFT, RIGHT, FULL OUTER) and filters (e.g., IS NULL, IS NOT NULL, NOT IN). Objectives include analyzing employee-department relationships, identifying gaps like unassigned employees or empty departments, and filtering specific records for organizational insights.

# Key Components:

1. Joins:

    INNER JOIN: Combines records where there is a match in both tables.
    E.g., Match employees to departments (Query 1).

    LEFT JOIN: Includes all rows from the left table (EMP) and matches from the right table (DEPT). Unmatched rows in the right table return NULL.
    E.g., Include employees even if they don't belong to a department (Query 2).

    RIGHT JOIN: Includes all rows from the right table (DEPT) and matches from the left table (EMP). Unmatched rows in the left table return NULL.
    E.g., Include all departments, even those without employees (Query 3).

    FULL OUTER JOIN: Combines all rows from both tables. Rows without matches in either table return NULL for columns from the unmatched table.
    E.g., Include all employees and all departments (Query 4).

2. Filtering Conditions:
   

    IS NOT NULL: Filters rows where a column has a non-NULL value.
    E.g., Employees belonging to a department (Query 5).

    IS NULL: Filters rows where a column has a NULL value.
    E.g., Employees with no commission (Query 6).

3. Subqueries:


    NOT IN Subquery: Filters rows where a value in the main query does not exist in the result of the subquery.
    E.g., Departments that have no employees (Query 7).

# Summary of Intentions:

Combine data from two tables to show relationships (INNER, LEFT, RIGHT, FULL OUTER JOIN).

Extract specific data based on the presence or absence of values (IS NULL and IS NOT NULL).

Use subqueries to identify unmatched records (e.g., departments without employees).

