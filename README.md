# Finals-Lab-Task-1-MySQL-Basics

In this task, we used MySQL to build a working database and learned how to correctly write and run the necessary SQL queries. Our job was to create several tables representing a sample company, which were then connected through relationships.

These are the guide given by our instructor:

### Task 1: Create the employees table
- employee_id a unique number, set it to auto-increment, and used it as the primary key.
- employee_name a text field (up to 255 characters) and made sure it can't be empty.
- manager_id an integer that links to employee_id from the same table.

### Task 2: Create the departments table
- department_id a unique number, set it to auto-increment, and used it as the primary key.
- department_name a text field (up to 255 characters) and made sure it can't be empty.

### Task 3: Create the employee_departments table
- employee_id an integer that links to employee_id in the employees table.
- department_id an integer that links to department_id in the departments table.
- Set the combination of employee_id and department_id as the primary key.

### Task 4: Create the employee_projects table
- employee_id an integer that links to employee_id in the employees table.
- project_name a text field (up to 255 characters) and made sure it can't be empty.

### Task 5: Create the managers table
- manager_id a unique number, set it to auto-increment, and used it as the primary key.
- employee_id an integer that links to employee_id in the employees table.

## Query statements
- Task - 1 Employee Table Query
Alt Text

- Task - 2 Department Table Query
Alt Text

- Task - 3 Employee Department Table Query
Alt Text

- Task - 4 Project Table Query
Alt Text

- Task - 5 Managers Table Query
Alt Text

## Table Structures
- Task 1 - Employee Table Structure
Alt Text

- Task 2 - Department Table Structure
Alt Text

- Task 3 - Employee Department Table Structure
Alt Text

- Task 4 - Project Table Structure
Alt Text

- Task 5 - Managers Table Structure
Alt Text

## Entity-Relational Schema
Relation Schema attached below
