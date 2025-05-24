## Final-Lab-Task-1 
This portfolio focuses on learning MySQL through a sample company database. It includes writing basic SQL queries, creating tables, and showcasing the overall database design. Additionally, it features SQL files that demonstrate how the database and tables were created.


**Step 1: Create the Employees Table:**

* Set `employee_id` as a unique integer that auto-increments and serves as the primary key of the table.
* Set `employee_name` as a `VARCHAR` with a maximum of 255 characters and ensure it cannot be null.
* Set `manager_id` as an integer that acts as a foreign key, referencing the `employee_id` within the same table.

**Step 2: Create the Departments Table:**

* Set `department_id` as a unique, auto-incrementing integer that functions as the primary key of the table.
* Set `department_name` as a `VARCHAR` field with a limit of 255 characters, and ensure it cannot be null.

**Step 3: Create the Employee\_Departments Table:**

* Set `employee_id` as an integer foreign key referencing the `employees` table.
* Set `department_id` as an integer foreign key referencing the `departments` table.
* Use a composite primary key consisting of `employee_id` and `department_id`.

**Step 4: Create the Employee\_Projects Table:**

* Set `employee_id` as an integer foreign key referencing the `employees` table.
* Set `project_name` as a non-null `VARCHAR` with a limit of 255 characters.

**Step 5: Create the Managers Table:**

* Set `manager_id` as a unique, auto-incrementing integer that serves as the primary key.
* Set `employee_id` as an integer foreign key referencing the `employees` table.


## Query Statements

# 1. Employees Table:
![Image](https://github.com/user-attachments/assets/f0eb396a-47e3-4628-a980-6eeb9d4e0856)

# 2. Department Table:
![Image](https://github.com/user-attachments/assets/a29336be-7c94-4bf6-83a5-9d7bc50fc353)

# 3. Employee Departments:
![Image](https://github.com/user-attachments/assets/981973d8-d32a-42b5-9e3f-7d7764d1b4be)

# 4. Employee Projects:
![Image](https://github.com/user-attachments/assets/357de5c9-ae74-41b6-8444-bbaface9aebe)

# 5. Manager Table:
![Image](https://github.com/user-attachments/assets/3485ab65-03fe-4365-be1d-bc5e65e54d66)

## Table Structure
# 1. Employees Table:
![Image](https://github.com/user-attachments/assets/cc705a4d-db69-44cd-a7be-a0f4a50ec258)

# 2. Department Table:
![Image](https://github.com/user-attachments/assets/eed4ecdd-ad3f-4d8b-816c-36a80b0cac6f)

# 3. Employee Departments:
![Image](https://github.com/user-attachments/assets/be6a4c89-7447-4bb7-a484-55b611c7ea35)

# 4. Employee Projects:
![Image](https://github.com/user-attachments/assets/a5a5ef85-403f-40c0-8037-fe3f6a38bfd6)

# 5. Manager Table:
![Image](https://github.com/user-attachments/assets/733883a1-da35-4bc2-80fd-d0fdc2be42cd)

## ER Diagram:
![Image](https://github.com/user-attachments/assets/5f2c6cc7-5c93-4015-94fc-3e57c50707de)
