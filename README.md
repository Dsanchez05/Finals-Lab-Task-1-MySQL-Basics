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
- Task - 1 Employee Table Query Statements

![Screenshot 2025-04-13 204504](https://github.com/user-attachments/assets/8b042284-796a-4d4c-80c3-d436f7e9cce3)

- Task - 2 Department Table Query Statements

![Screenshot 2025-04-13 204512](https://github.com/user-attachments/assets/9c5c7f27-e053-4139-920b-84d2589cc78c)

- Task - 3 Employee Department Table Query Statements

![Screenshot 2025-04-13 204529](https://github.com/user-attachments/assets/4266781c-8b70-4930-93c0-478d32cd3830)


- Task - 4 Project Table Query Statements

![Screenshot 2025-04-13 204536](https://github.com/user-attachments/assets/abff69e3-b6ae-4a0d-8ea7-7a613103a8fd)


- Task - 5 Managers Table Query Statements

![Screenshot 2025-04-13 204548](https://github.com/user-attachments/assets/721909de-42e8-465d-b139-2957d0a2fc75)


## Table Structures
- Task 1 - Employee Table Structure

![Screenshot 2025-04-13 195144](https://github.com/user-attachments/assets/19546eb1-07e0-4308-af29-77391a5c34c6)

- Task 2 - Department Table Structure

![Screenshot 2025-04-13 195215](https://github.com/user-attachments/assets/b72f87e8-d858-4420-9c96-46f36bff41dc)

- Task 3 - Employee Department Table Structure

![Screenshot 2025-04-13 195227](https://github.com/user-attachments/assets/2516ce18-6e29-4ad0-b8be-79c5c8986c6d)

- Task 4 - Project Table Structure

![Screenshot 2025-04-13 195246](https://github.com/user-attachments/assets/6f37dab3-624d-47de-866d-9c341d3b02b8)


- Task 5 - Managers Table Structure

![Screenshot 2025-04-13 195257](https://github.com/user-attachments/assets/eed15bb5-e27c-4f86-80c5-c181c2d27b62)


## Entity-Relational Schema
Relation Schema attached below

![Screenshot 2025-04-13 194418](https://github.com/user-attachments/assets/91e16065-98d6-40b2-96e3-a8308793a76f)
