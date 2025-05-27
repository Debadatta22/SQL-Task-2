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

# 📥 Sample Data

The table includes 15 rows of sample employee data across different departments like Sales, HR, IT, and Marketing with varying scores and review dates.

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

# ✅ Outcome

This task helps visualize employee performance metrics, detect departmental trends, and identify top performers using advanced SQL queries in Oracle. It demonstrates effective use of SQL for real-time data analysis and reporting.

