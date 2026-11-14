# Task 1: Writing Basic SELECT Queries

## 📌 Overview
This task focuses on learning the fundamentals of SQL by writing basic `SELECT` queries to retrieve data from database tables.

The objective is to understand how to extract specific information from a database using different SQL clauses and conditions.

## 🎯 Objective
To practice retrieving data from tables using SQL commands such as:
- `SELECT`
- `WHERE`
- `AND` and `OR`
- `LIKE`
- `BETWEEN`
- `ORDER BY`
- `LIMIT`

## 🛠️ Tools Used
- DB Browser for SQLite
- SQL

## 📂 Dataset / Table
**Table Name:** `Employees`

The Employees table contains the following columns:

| Column Name | Description |
|-------------|-------------|
| employee_id | Unique employee ID |
| first_name | Employees first name |
| last_name | Employees Surname |
| city | Employee city |
| department | Department name |
| age | Employee age |
| salary | Employee salary |
| joining_date | Date of joining |


## 📝 Topics Covered

1. Retrieving all records using `SELECT *`.
2. Selecting specific columns from a table.
3. Filtering records using `WHERE`.
4. Applying multiple conditions using `AND` and `OR`.
5. Pattern matching using `LIKE`.
6. Filtering values within a range using `BETWEEN`.
7. Sorting records using `ORDER BY`.
8. Limiting query results using `LIMIT`.

## 💻 Sample SQL Queries

**1. Display all employee records**
```sql
SELECT * FROM Employees;
```

**2. Display employee names and salaries**
```sql
SELECT employee_name, salary
FROM Employees;
```

**3. Find employees working in the IT department**
```sql
SELECT *
FROM Employees
WHERE department = 'IT';
```

**4. Sort employees by salary in descending order**
```sql
SELECT *
FROM Employees
ORDER BY salary DESC;
```

**5. Display the first 5 employee records**
```sql
SELECT *
FROM Employees
LIMIT 5;
```

## 📚 Learning Outcomes

After completing this task, I gained practical knowledge of:

- Writing basic SQL queries.
- Retrieving complete and specific records.
- Filtering data based on conditions.
- Applying multiple filtering conditions.
- Searching data using pattern matching.
- Sorting and limiting query results.


## 🚀 Conclusion

This task helped me build a strong foundation in SQL by practicing basic data retrieval operations. These concepts are essential for data analysis and will be useful in solving real-world SQL problems.

