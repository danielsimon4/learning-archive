# SQL

<br>

### SQL Cheat Sheet

| Action | SQL |
| - | - |
| Create a New Database | CREATE DATABASE database_name; |
| Select an Existing Database to Work With | USE database_name; |
| Update an Existing Database | ALTER DATABASE database_name; |
| Delete an Existing Database | DROP DATABASE database_name; |

| Action | SQL |
| - | - |
| Create a New Table | CREATE TABLE table_name (<br>column1_name INT PRIMARY KEY, <br>column2_name VARCHAR(50) NOT NULL, <br>column3_name DECIMAL(10, 2) UNIQUE, <br>... <br>); |
| Add rows to an Existing Table | INSERT INTO table_name (column1_name, column2_name, column3_name, ...) <br>VALUES <br>(c1, c2, c3, ...), <br>(c1, c2, c3, ...), <br>...; |
| Update an Existing Table | ALTER TABLE table_name <br> ADD COLUMN new_column INT; |



