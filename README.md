# SQL_EXCERCISE
# SQL Employee Data Analysis

## About the Project

This is a beginner SQL project using an employee dataset.

The project focuses on retrieving, filtering, and sorting employee data using SQL.

## Dataset

The `employees` table contains:

- Employee ID
- First name
- Last name
- Department
- Salary
- Hire date
- City

## SQL Skills Practiced

- SELECT
- FROM
- WHERE
- AND
- OR
- NOT
- IN
- DISTINCT
- ORDER BY
- LIMIT

## Questions Answered

Some of the questions explored in this project include:

1. Retrieve all employee information.
2. Find unique departments.
3. Find employees ordered by salary.
4. Find the top 3 highest-paid employees.
5. Find employees in the IT department.
6. Find Finance employees earning more than 60,000.
7. Find employees in HR or Marketing.
8. Find employees who are not in IT.
9. Find employees in IT, HR, or Finance.
10. Find employees in IT with a salary above 65,000 and who live in Johannesburg.

## Example Query

```sql
SELECT id, first_name, last_name, department, salary, city
FROM employees
WHERE department = 'IT'
AND salary > 65000
AND city = 'Johannesburg'
What I Learned

Through this project, I practised using SQL to:

Retrieve data
Filter data
Sort data
Find unique values
Apply multiple conditions
Answer simple business questions using data
