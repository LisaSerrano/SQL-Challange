  # Pewlett Hackard Employee Database Analysis

## Background
As a newly hired data engineer at Pewlett Hackard, your first major task is to conduct a research project on the employees who worked at the company during the 1980s and 1990s. The available data consists of six CSV files containing information about the employees, departments, salaries, titles, and more.

## Instructions
This challenge is divided into three parts: data modeling, data engineering, and data analysis.

### Data Modeling
- Inspect the provided CSV files and sketch an Entity Relationship Diagram (ERD) representing the tables' relationships. You can use tools like QuickDBD for this task.

### Data Engineering
- Create a table schema for each of the six CSV files, specifying data types, primary keys, foreign keys, and other constraints.
- Ensure that primary keys are unique and create composite keys if necessary.
- Create tables in the correct order to handle foreign keys.
- Import each CSV file into its corresponding SQL table.

### Data Analysis
Perform the following data analysis tasks using SQL queries:
1. List employee number, last name, first name, sex, and salary of each employee.
2. List first name, last name, and hire date for employees hired in 1986.
3. List the manager of each department with department number, department name, employee number, last name, and first name.
4. List department number for each employee with employee number, last name, first name, and department name.
5. List first name, last name, and sex of each employee named Hercules with last name starting with the letter B.
6. List each employee in the Sales department with employee number, last name, and first name.
7. List each employee in the Sales and Development departments with employee number, last name, first name, and department name.
8. List the frequency counts of employee last names in descending order.

## Conclusion
By completing these tasks, we will gain insights into the composition of Pewlett Hackard's workforce during the 1980s and 1990s, allowing for informed decision-making and strategic planning.
