# Student Record Management SQL Project

This project is based on a Student Record Management system created using PostgreSQL in pgAdmin.

## Project Overview
In this project, data was imported into pgAdmin from Excel/CSV files and then various SQL operations were performed on the database.

The project includes:
- Basic SQL Queries
- Advanced SQL Queries
- Database Management and Security tasks
- Functions
- Triggers
- Stored Procedure / PLpgSQL
- View creation
- Index creation
- Role and privilege management

## Tools Used
- PostgreSQL
- pgAdmin
- SQL
- Excel / CSV files
- MS Word

## Project Files
This repository contains:

1. **Project documentation file**  
   Contains the SQL project explanation and all tasks performed.

2. **Query screenshots file**  
   Contains screenshots of all SQL queries and their outputs.

## Tasks Performed

### Part 1: Basic Queries
1. Retrieved Data Science courses costing less than 2000 and sorted them by price  
2. Counted number of courses in each category  
3. Found categories with total enrollments greater than 150  
4. Displayed top 5 most expensive courses  
5. Listed 6th through 10th students from London  

### Part 2: Advanced Queries
6. Displayed each course with its instructor  
7. Listed all instructors with their course titles, including those not teaching any course  
8. Found student name, course title, and instructor name for enrollments from New York students  
9. Found students enrolled in Cloud category courses  
10. Retrieved courses priced above average course price  
11. Identified instructor teaching the highest number of courses  
12. Found unique names from students and instructors  
13. Found course IDs with enrollments in both 2024 and 2025  
14. Found course IDs with enrollments in 2025 but not in 2024  
15. Ranked courses by price within each category  
16. Calculated difference between course price and category average price  

### Part 3: Database Management and Security
17. Created function `get_course_enrollment_count`  
18. Created audit table `course_price_audit`  
19. Created trigger to log course price updates  
20. Created procedure/function `add_new_enrollment`  
21. Calculated months passed since earliest enrollment date  
22. Found student names containing 'Jackson' using case-insensitive search  
23. Created role `auditor` and managed permissions  
24. Created view `v_instructor_performance`  
25. Created non-unique index on course category  

## Learning Outcomes
Through this project, I practiced:
- Data import in pgAdmin
- Writing basic and advanced SQL queries
- Joins, grouping, sorting, filtering
- Aggregate functions
- Window functions
- Set operations
- Functions and stored procedures
- Triggers and audit logging
- Roles, privileges, and views
- Indexing for performance improvement

## Notes
- Data was first imported into PostgreSQL using pgAdmin.
- Query execution and outputs are included in the uploaded Word files.
- Screenshots of query results are provided for reference.

## Author
Tejas Kolhe
