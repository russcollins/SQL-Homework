# sql-challenge
This repository is a research project on employees of Pewlett Hackard from the 1980s and 1990s. Starting with six CSV files, QuickDBD was used to sketch out an ERD of the tables. The table schema was then imported into an SQL database with specified data types, primary keys, foreign keys, and other constraints. If a table did not have a unique column to be a primary key, a composite key was created. 

After importing the original CSV files, the following queries were run in the completed database:
 1. List the following details of each employee: employee number, last name, first name, sex, and salary.
 2. List first name, last name, and hire date for employees who were hired in 1986.
 3. List the manager of each department with the following information: department number, department name, the manager's employee number, last name, first name.
 4. List the department of each employee with the following information: employee number, last name, first name, and department name.
 5. List first name, last name, and sex for employees whose first name is "Hercules" and last names begin with "B."
 6. List all employees in the Sales department, including their employee number, last name, first name, and department name.
 7. List all employees in the Sales and Development departments, including their employee number, last name, first name, and department name.
 8. In descending order, list the frequency count of employee last names, i.e., how many employees share each last name.

The database was then imported into Pandas to run further analysis. The pandas code creates a histogram to visualize the most common salary ranges for employees, as well as a bar chart of average salary by title. Finally, the code searches for the given employee ID number "499942".

