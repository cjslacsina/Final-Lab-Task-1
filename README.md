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
![Image](https://github.com/user-attachments/assets/ae5115de-c211-4fe0-ae84-7a0695a2d2ff)

# 2. Department Table:
![Image](https://github.com/user-attachments/assets/83aad58a-6b77-4d74-b90a-a4a1f414b444)

# 3. Employee Departments:
![Image](https://github.com/user-attachments/assets/338e8a42-10ef-45f5-8b35-81f62a26b5af)

# 4. Employee Projects:
![Image](https://github.com/user-attachments/assets/7013c794-d78b-45d0-b4a9-b2cff96dfd84)

# 5. Manager Table:
![Image](https://github.com/user-attachments/assets/85faf40b-4982-4be6-9e5e-05280c8fc1b5)

## Table Structure
# 1. Employees Table:
![Image](https://github.com/user-attachments/assets/e7d53d0f-a6ed-4b0f-8140-2580f348bb3a)

# 2. Department Table:
![Image](https://github.com/user-attachments/assets/36bf2ed4-be47-45af-99e5-bf40241e8434)

# 3. Employee Departments:
![Image](https://github.com/user-attachments/assets/06770a54-7f15-4d40-87f9-c705714f59c2)

# 4. Employee Projects:
![Image](https://github.com/user-attachments/assets/8205fe7a-a409-48b5-92fd-b61afac9d1c8)

# 5. Manager Table:
![Image](https://github.com/user-attachments/assets/c3bdd751-8772-4929-85f4-6f5ab1b45cd4)

## ER Diagram:
![Image](https://github.com/cjslacsina/EDM-V3/blob/7079baaba85f2bc663fdb1dde9d11bb12a1dcc16/image2/LACSINA_EER_DIAGRAM.PNG)
