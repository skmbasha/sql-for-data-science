On Day 4 of my SQL for Data Science learning journey, I learned about DML (Data Manipulation Language) commands, which are used to interact with and manipulate data stored inside database tables.

DML commands help in performing operations such as inserting new data, updating existing data, deleting records, and retrieving data for analysis.

DML Commands with Examples

1. INSERT
Used to add new records into a table.

Example:

INSERT INTO employees (id, name, salary)
VALUES (1, 'Basha', 30000);

2. SELECT
Used to retrieve data from a table.

Example:

SELECT * FROM employees;

3. UPDATE
Used to modify existing data in a table.

Example:

UPDATE employees
SET salary = 35000
WHERE id = 1;

4. DELETE
Used to remove specific records from a table.

Example:

DELETE FROM employees
WHERE id = 1;
Summary

DML commands are essential for working with data inside tables. They allow us to insert, retrieve, update, and delete data efficiently. These operations are widely used in data analysis to manage and maintain datasets.
