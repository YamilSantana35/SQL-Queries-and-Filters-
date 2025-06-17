# SQL-Queries-and-Filters-

Project Overview

This project simulates a real-world scenario where a security professional investigates potential security issues in a large organization using SQL. The primary goal was to analyze login attempts and employee data from two key tables: `log_in_attempts` and `employees`.

The analysis included identifying:
- Failed login attempts after business hours
- Login attempts on specific suspicious dates
- Logins from outside of Mexico
- Employees in specific departments and locations

The insights from these queries were used to inform incident response and guide system updates across the organization.

Lessons Learned
  Date and Time Filters: Learned how to use comparison operators (>, <) with time fields and exact matches with dates to narrow down login activity. Using LIKE and Wildcards: Leveraged the LIKE operator and % wildcard to match partial values in string fields like country and office. AND, OR, NOT Operators: Practiced combining conditions to build complex filters that target very specific subsets of data. Security Use Cases with SQL: Gained practical experience applying SQL to real-world cybersecurity scenarios, particularly around access control and incident response.

Summary
  This project demonstrated the power of SQL in identifying and investigating security-related patterns in system and employee data. By combining conditional filters, logical operators, and string matching, I was able to simulate how a SOC analyst or security professional would use SQL in a real incident response context.
