# CODTECH-Task2

**COMPANY**: CODTECH IT SOLUTIONS

**NAME**: LATIKA SATISH KARKERA

**INTERN ID**: CT08DS9741

**DOMAIN**: SQL

**BATCH DURATION**: DECEMBER 10TH 2024 TO JANUARY 10TH 2025

#OVERVIEW

This project involves the creation and management of a relational database system to handle employee records, including personal details, job positions, departmental affiliations, and salary information. The goal was to design a robust and scalable database structure that supports managing various aspects of employee records in a corporate environment. The database includes several interrelated tables, each representing a distinct entity in the system. The project also includes SQL queries to manage employee data, including retrieval, updates, and deletion of records.

Database Design
The database for employee management consists of three primary tables:

Department Table:

This table stores information about the departments within the organization.
It includes two columns: a primary key department_id, which uniquely identifies each department, and department_name, which stores the name of the department.
The department table helps track the various divisions of the organization, such as HR, Engineering, Marketing, and so on.
Job Position Table:

This table holds data about the different job positions available in the company.
Similar to the department table, it consists of a primary key position_id, which uniquely identifies each position, and position_name, which stores the title of the job position, such as "Manager," "Developer," or "Sales Representative."
This table helps organize employee roles and tracks the different job titles in the organization.
Employee Table:

The employee table is the central table in this database and stores information about the employees themselves.
It includes several columns such as employee_id, which uniquely identifies each employee, first_name, last_name, birth_date, gender, and address, which store personal details of the employees.
The table also includes foreign keys: department_id and position_id, which link each employee to a specific department and job position, respectively.
The salary_amount column tracks the salary of each employee, ensuring accurate payroll management.
These three tables are linked by the department_id and position_id foreign keys in the employee table, establishing relationships between employees, departments, and job positions. This relational design ensures efficient data retrieval and the ability to join tables to gather meaningful information.

Instructions Followed
The instructions for this project required the creation of complex relationships between the employees, departments, and job positions, as well as the implementation of various queries to manage and analyze employee records. Below is a breakdown of how these instructions were followed:

1. Table Creation
The first step involved creating the three primary tables: department, job_position, and employee. Each table was designed to handle specific aspects of the employee management system:

The department table tracks different departments.
The job_position table stores job titles.
The employee table stores detailed employee information, linking each employee to a department and job position.
2. Populating Tables
After the tables were created, initial data was inserted into the department and job_position tables to represent the different departments and positions within the organization. A variety of departments like HR, Engineering, Sales, Marketing, and others were added. Similarly, job positions such as Manager, Developer, Sales Representative, and others were inserted into the job_position table.

Next, the employee table was populated with data for several employees, including their personal information (name, birth date, gender, address), department and job position assignments, and salary amounts. This populated dataset represents the employees working across various departments and job roles.

3. Query Implementation
The project required a series of SQL queries to perform different actions:

Show All Employee Details with Department and Job Position: This query uses a LEFT JOIN to combine data from the employee, department, and job_position tables. It retrieves all employee details along with their respective department name and job position.

Get the Highest Salary in Each Department: This query groups the employee data by department and uses the MAX() function to find the highest salary within each department. It demonstrates how to aggregate data and retrieve the maximum salary per department.

Update Employee Salary: An update query was implemented to change the salary of a specific employee. This query modifies the salary of an employee by matching their employee_id and updating the salary_amount field. This demonstrates how salary adjustments can be made.

Delete Employee Record: A delete query was executed to remove an employee’s record from the employee table using the employee_id. This action shows how to manage and delete employee records from the system.

List Employees Who Earn More Than a Specific Salary: A query was designed to list employees who earn more than a given salary threshold. It uses a WHERE clause to filter the records based on the salary_amount, ensuring only employees who meet the condition are displayed.

4. Managing Employee Records and Departmental Information
The queries executed in this project cover the essential tasks of employee management:

Retrieving employee details along with their department and job position.
Analyzing salary data by retrieving the highest salary in each department.
Updating employee records to reflect changes in salary.
Deleting records when necessary.
Filtering employees based on specific salary conditions.
Conclusion
Through this project, a comprehensive employee management database system was developed using SQL. The relational design with interlinked tables for employees, departments, and job positions allows for efficient data storage and retrieval. The SQL queries demonstrated a variety of operations, including data retrieval, aggregation, updates, and deletions. This system enables the management of employee records in a corporate environment, ensuring that all employee data is accurately tracked and accessible for analysis or reporting. This project successfully showcases the use of SQL for managing employee records and departmental information in a real-world business setting.

#OUTPUT
