# mySQL-Week-1-Coding-Assignment
use employees;
show tables;
SELECT * FROM employees;
SELECT * FROM employees WHERE birth_date < '1965-01-01';
SELECT * FROM employees WHERE gender = 'f' AND hire_date > '1990-01-01';
SELECT * FROM employees WHERE last_name LIKE 'f%' LIMIT 50;
SELECT * FROM employees LIMIT 50;
UPDATE employees SET first_name = 'Bob' WHERE emp_no = 10023;
SELECT * FROM employees LIMIT 50;
UPDATE employees SET hire_date = '2002-01-01' WHERE last_name LIKE 'p%' OR first_name LIKE 'p%';
DELETE FROM employees WHERE emp_no < 10000;
SELECT * FROM employees;
DELETE FROM employees WHERE emp_no = 10048;
DELETE FROM employees WHERE emp_no = 10099;
DELETE FROM employees WHERE emp_no = 10234;
DELETE FROM employees WHERE emp_no = 20089;
SELECT * FROM employees;
