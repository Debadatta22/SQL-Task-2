# SQL-Task-2
CODTECH INTERNSHIP TASK-2 SOLUTIONS(using window functions, subqueries, and CTEs)

# PERFORMED & SUBMITTED BY:

--TASK PERFORMED BY: DEBADATTA ROUT

--Intern ID : CT04DN790

--DOMAIN: SQL

--DURATION: 4 WEEKS

--MENTOR: Neela Santhosh

# 📝 Task Overview

This SQL project involves creating a table to store employee performance data and executing queries to analyze trends and patterns in their scores. It focuses on the use of Oracle SQL functions, conditions, and analytical queries to gain insights from data.

# 📂 Table Used

EMPLOYEE_SCORES

This table stores performance data for each employee including:

EMP_ID (Employee ID - Primary Key)

NAME (Employee Name)

DEPARTMENT (Department Name)

SCORE (Performance Score)

REVIEW_DATE (Date of Review)

![Image](https://github.com/user-attachments/assets/236f1540-c7b1-4db9-b4e6-b24aef7f1aee)

# 📥 Sample Data

The table includes 15 rows of sample employee data across different departments like Sales, HR, IT, and Marketing with varying scores and review dates.

![Image](https://github.com/user-attachments/assets/72669075-cc14-4970-a04b-8611f5d0e1b2)

![Image](https://github.com/user-attachments/assets/5e99be86-e0f1-47f1-a937-eab086ccd7f2)
#🛠️ SQL Concepts Used

CREATE TABLE – To define the schema for employee performance data.

INSERT INTO – To add multiple rows of data into the table.

SELECT – To retrieve and view data.

WHERE – To apply conditions and filter results.

GROUP BY – To group data for aggregation.

ORDER BY – To sort the results based on column values.

RANK() OVER (PARTITION BY ...) – A window function to rank employees within departments.

WITH Clause (CTE) – Used for modular and readable subqueries.

# 📈 Key Analytical Queries Performed

Ranking Employees by Score: Shows how each employee ranks within their department.

Above-Average Performers by Department: Lists employees whose scores are higher than their department’s average.

Top Scorers: Identifies the highest scorer(s) in each department.

Monthly Performance Trend: Shows how average scores vary by month.

Score Distribution: Provides a breakdown of scores per department.

![Image](https://github.com/user-attachments/assets/1b715227-2761-4c93-a60c-5f692c9c99fa)

![Image](https://github.com/user-attachments/assets/d4c7e53a-8067-444f-a2a7-3e5bdc54adc8)

# ✅ Outcome

This task helps visualize employee performance metrics, detect departmental trends, and identify top performers using advanced SQL queries in Oracle. It demonstrates effective use of SQL for real-time data analysis and reporting.

For = 

1. Rank employees by SCORE within each DEPARTMENT Output
![Image](https://github.com/user-attachments/assets/1bd58b70-0a10-4f6a-b1e1-314d213e9e6e)

2. Employees who scored above department average output
![Image](https://github.com/user-attachments/assets/74f34dd4-1c75-46e5-91a1-d87f33f6a0db)

3. Top scorer in each department output


4. Average score by department output

5. Monthly average score trend output

6. Employees who scored above overall average output

7. Department-wise score distribution output

