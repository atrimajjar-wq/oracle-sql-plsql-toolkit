Oracle SQL & PL/SQL Toolkit

Project Overview

This project demonstrates practical Oracle SQL and PL/SQL skills through an employee and department database. It includes sample data, reporting queries, salary analysis, and a stored procedure with input validation and error handling.

Technologies Used

Oracle SQL

PL/SQL

Relational database design

SQL joins and subqueries

Aggregate and analytic functions

Stored procedures and exception handling

Database Structure

PTK_DEPARTMENTS

Stores department IDs, department names, and locations.

PTK_EMPLOYEES

Stores employee IDs, names, job titles, salaries, department IDs, and hire dates.

A primary key uniquely identifies each record, and a foreign key connects employees to departments.

Project Features

Employee and department report using JOIN.

Department-level employee counts and salary statistics.

Identification of employees earning above the company average.

Highest-paid employee identification by department using RANK.

Identification of employees earning above their department average.

PL/SQL salary-increase procedure with percentage validation.

Error handling for invalid percentages and nonexistent employee IDs.

Project Files

01_create_tables.sql — creates the database tables.

02_insert_sample_data.sql — inserts sample departments and employees.

03_sql_queries.sql — contains five SQL reporting queries.

04_salary_procedure.sql — creates the salary-increase procedure.

Sample Dataset

The project is designed to use 30 departments and 130 employee records. The data is synthetic and created for educational and demonstration purposes.

How to Run

Open an Oracle SQL environment.

Run 01_create_tables.sql in a clean project schema.

Run 02_insert_sample_data.sql.

Run individual queries from 03_sql_queries.sql.

Run 04_salary_procedure.sql to create the stored procedure.

Test the procedure using a sample employee ID.

Note: The creation and sample-data scripts are intended for a clean schema. Do not rerun them against already-populated tables without resetting the project data first.

Purpose

This portfolio project demonstrates hands-on practice with Oracle SQL, relational database queries, reporting, and PL/SQL programming.