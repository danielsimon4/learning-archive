# SQL

<br>

### Database Level

| Action | SQL |
| - | - |
| Create a New Database | CREATE DATABASE database_name; |
| Select an Existing Database to Work With | USE database_name; |
| Update an Existing Database | ALTER DATABASE database_name; |
| Delete an Existing Database | DROP DATABASE database_name; |

<br>

### Table Level

| Action | SQL |
| - | - |
| Create a New Table | CREATE TABLE table_name (<br>column1_name INT PRIMARY KEY, <br>column2_name VARCHAR(50) NOT NULL, <br>column3_name DECIMAL(10, 2) UNIQUE, <br>... <br>); |
| Add rows to an Existing Table | INSERT INTO table_name (column1_name, column2_name, ...) <br>VALUES <br>(c1, c2, ...), <br>(c1, c2, ...), <br>... <br>; |
| Update an Existing Table | ALTER TABLE table_name <br> ADD COLUMN column_name DATA_TYPE; |
| Delete an Existing Table | DROP TABLE table_name; |

<br>

### Quering Data

| Action | SQL |
| - | - |
| Return All Rows and Columns | SELECT * FROM table_name; |
| Return Unique Values From a Column | SELECT DISTINCT column_name FROM table_name; |
| Filter Rows Based On a Condition | SELECT * FROM table_name WHERE column_name > number;
| Limit Number of Rows Returned | SELECT * FROM table_name LIMIT number;
