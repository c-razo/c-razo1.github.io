## Steps and Explanations

**Step 1: Open the MariaDB Shell**

Explanation: I opened the MariaDB shell to interact with the database on my Kali Linux VM. Accessing the database shell is essential for executing SQL commands directly and managing data effectively.
Command Used: sudo mysql -u root


**Step 2: Create the Organization Database**

Explanation: I created the organization database as the primary container for storing tables used in the lab. Databases organize data into tables, allowing efficient storage and retrieval of information for analysis.
Command Used: CREATE DATABASE organization;
Screenshot: Documented the successful creation of the database.


**Step 3: Create the log_in_attempts Table**

Explanation: I set up the log_in_attempts table to record login data, including timestamps, success status, and country of origin. This table helped simulate data related to login activities—common data for cybersecurity reviews.
Command Used: CREATE TABLE log_in_attempts (...)
Screenshot: Captured the table creation process.


**Step 4: Insert Sample Data into log_in_attempts**

Explanation: I populated the log_in_attempts table with sample data. This included both successful and failed login attempts at various times, dates, and countries. Inserting data allowed me to work with a realistic dataset for the lab.
Command Used: INSERT INTO log_in_attempts (...) VALUES (...)
Screenshot: Documented the successful insertion of sample data.


**Step 5: Run Query for Task 1 (After-Hours Failed Login Attempts)**

Explanation: I used the AND operator to filter for login attempts that failed after business hours. This simulates a scenario where after-hours access could indicate suspicious activity.
- SQL Query: SELECT * FROM log_in_attempts WHERE login_time > '18:00:00' AND success = 0;
Screenshot: Captured the query and results.


**Step 6: Run Query for Task 2 (Login Attempts on Specific Dates)**

Explanation: Using the OR operator, I filtered for login attempts on specified dates. Filtering by date is useful for investigating incidents on particular days.
SQL Query: SELECT * FROM log_in_attempts WHERE login_date = '2022-05-08' OR login_date = '2022-05-09';
Screenshot: Documented the query and its results.


**Step 7: Run Query for Task 3 (Login Attempts Outside of Mexico)**

Explanation: I used the NOT and LIKE operators to retrieve login attempts that didn’t originate from Mexico. This type of filter is valuable for narrowing down events by geographic location.
SQL Query:SELECT * FROM log_in_attempts WHERE NOT country LIKE 'MEX%';
Screenshot: Captured the query and results.


**Step 8: Create the employees Table**

Explanation: I created an employees table to store employee information, including usernames, departments, and office locations. This table helped simulate data for querying specific departments and locations.
Command Used: CREATE TABLE employees (...)
Screenshot: Documented the table creation process.


**Step 9: Insert Sample Data into employees**

Explanation: I populated the employees table with sample employee records across different departments and locations. Adding sample data provided a foundation for testing additional queries.
Command Used: INSERT INTO employees (...) VALUES (...)
Screenshot: Captured the data insertion process.


**Step 10: Run Query for Task 4 (Employees in Marketing, East Building)**

Explanation: I used the AND and LIKE operators to filter for employees in the Marketing department located in the East building. This query simulated retrieving department-specific employee data by location.
SQL Query: SELECT * FROM employees WHERE department = 'Marketing' AND office LIKE 'East%';
Screenshot: Documented the query and results.


**Step 11: Run Query for Task 5 (Employees in Finance or Sales Departments)**

Explanation: I used the OR operator to retrieve employees in either the Finance or Sales departments. This type of query is common for applying policies or updates across multiple departments.
SQL Query: SELECT * FROM employees WHERE department = 'Finance' OR department = 'Sales';
Screenshot: Captured the query and results.


**Step 12: Run Query for Task 6 (Employees Not in Information Technology)**

Explanation: I used the != operator to exclude employees in the Information Technology department. This exclusion filter is useful for targeting only non-IT departments for specific analyses.
SQL Query: SELECT * FROM employees WHERE department != 'Information Technology';
Screenshot: Documented the query and results.
