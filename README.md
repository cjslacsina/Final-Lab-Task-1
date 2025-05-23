## Final-Lab-Task-1 
This portfolio is about learning MySQL using a sample company database by writing simple SQL queries, creating tables, and showing the database design. It also includes SQL files that show how the database and tables were made.

# Step 1: Create the employees table:

* Set employee_id as a unique integer that auto-increments and serves as the table's primary key.  
* Set employee_name as a VARCHAR type with a maximum of 255 characters and it cannot be null.  
* Set manager_id as an integer that acts as a foreign key, linking back to the employee_id within the same table.

# Step 2: Create the departments table:

* Set department_id as a unique, auto-incrementing integer that functions as the primary key of the table.  
* Set  department_name as a VARCHAR field with a limit of 255 characters, and require that it cannot be null.

# Step 3: Create the employee_departments table:

* Set employee_id as an integer foreign key from employees.  
* Set department_id as an integer foreign key from departments.  
* Use a composite primary key of employee_id and department_id.

# Step 4: Create the employee_projects table:

* Set employee_id as an integer foreign key from employees.  
* Set project_name as a non-null VARCHAR (255 characters).

# Step 5: Create the managers table:

* Set manager_id as a unique auto-incrementing integer primary key.  
* Set employee_id as an integer foreign key from employees.

## Query Statements

# 1. Employees Table:
![Image]()

# 2. Department Table:
![Image]()

# 3. Employee Departments:
![Image]()

# 4. Employee Projects:
![Image]()

# 5. Manager Table:
![Image]()

## Table Structure
# 1. Employees Table:
![Image]()

# 2. Department Table:
![Image]()

# 3. Employee Departments:
![Image]()

# 4. Employee Projects:
![Image]()

# 5. Manager Table:
![Image]()

## ER Diagram:
![Image]()
