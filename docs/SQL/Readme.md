# Structured Query Language

SQL (Structured Query Language) is the standard language used to communicate with and manipulate relational databases. It is used for querying, updating, and managing data stored in a relational database management system (RDBMS).

### What is `RDBMS` ?
A Relational Database Management System (RDBMS) is a type of database management system that stores data in a structured format using rows and columns.

#### 1. Basics of SQL
- Relational Database Concepts
    - Tables, rows, and columns
    - Primary keys and foreign keys
    - Relationships between tables

#### 2. Data Definition Language (DDL)
- Creating Databases and Tables
    - `CREATE DATABASE`
    - `CREATE TABLE`
- Modifying Database Structure
    - `ALTER TABLE`
    - `ADD`, `DROP`, `MODIFY` columns
- Deleting Databases and Tables
    - `DROP DATABASE`
    - `DROP TABLE`
- Data Types
    - Numeric, string, date/time data types
    - Custom data types

#### 3. Data Manipulation Language (DML)

- Retrieving Data
   - `SELECT` statement
   - Selecting specific columns
   - Using aliases (`AS` keyword)
- Filtering Data
   - `WHERE` clause
   - Comparison operators (=, !=, <, >, <=, >=)
   - Logical operators (`AND`, `OR`, `NOT`)
- Sorting Data
   - `ORDER BY` clause
   - Sorting in ascending/descending order
- Limiting Results
   - `LIMIT` and `OFFSET` clauses
- Inserting Data
  - `INSERT INTO`
  - Inserting multiple rows
- Updating Data
  - `UPDATE` statement
  - Updating multiple rows
- Deleting Data
  - `DELETE FROM`
  - Deleting based on conditions

#### 4. Advanced Data Retrieval

- Aggregate Functions
    - `COUNT()`, `SUM()`, `AVG()`, `MIN()`, `MAX()`
- Grouping Data
    - `GROUP BY` clause
    - `HAVING` clause
- Joins
   - Inner join (`JOIN`)
   - Outer joins (`LEFT JOIN`, `RIGHT JOIN`, `FULL OUTER JOIN`)
   - Cross join (`CROSS JOIN`)
   - Self join
- Subqueries
   - Subqueries in `SELECT`, `FROM`, `WHERE`, and `HAVING` clauses
   - Correlated subqueries
- Set Operations
    - `UNION`, `UNION ALL`
    - `INTERSECT`
    - `EXCEPT`



Full-Text Search
Creating full-text indexes
Using full-text search queries
JSON and XML Data Handling
Storing JSON and XML data
Querying JSON and XML data
