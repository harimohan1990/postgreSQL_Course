

## 🟢 **PostgreSQL Course: Basics to Advanced**

---

## **Section 1: Introduction to PostgreSQL**

### 1.1 What is PostgreSQL?
- Overview and History
- Features of PostgreSQL
- Comparison with MySQL, SQLite, Oracle

### 1.2 Installing PostgreSQL
- On Windows, macOS, and Linux
- Using pgAdmin (GUI)
- Using the PostgreSQL CLI (`psql`)

---

## **Section 2: SQL Basics in PostgreSQL**

### 2.1 Database & Table Operations
- Creating and Deleting Databases
- Creating Tables
- Data Types in PostgreSQL (text, varchar, int, serial, timestamp, jsonb, etc.)
- Dropping and Altering Tables

### 2.2 CRUD Operations
- **INSERT**: Adding Data
- **SELECT**: Retrieving Data
- **UPDATE**: Modifying Data
- **DELETE**: Removing Data

### 2.3 Querying Data
- Filtering with `WHERE`
- Using `ORDER BY`, `LIMIT`, `OFFSET`
- Pattern Matching with `LIKE`, `ILIKE`
- NULL handling
- Aggregate Functions: `COUNT`, `SUM`, `AVG`, `MAX`, `MIN`

---

## **Section 3: Intermediate SQL Concepts**

### 3.1 Constraints
- `PRIMARY KEY`, `UNIQUE`, `NOT NULL`
- `FOREIGN KEY`, `CHECK`, `DEFAULT`

### 3.2 Joins
- INNER JOIN
- LEFT JOIN
- RIGHT JOIN
- FULL OUTER JOIN
- CROSS JOIN
- Self Join

### 3.3 Subqueries and CTEs
- Subqueries in `SELECT`, `FROM`, `WHERE`
- Common Table Expressions (`WITH` clause)

### 3.4 Indexing
- Why Use Indexes?
- Creating and Dropping Indexes
- Types: B-tree, Hash, GIN, GiST

---

## **Section 4: Advanced SQL in PostgreSQL**

### 4.1 Views and Materialized Views
- Creating Views
- Updating Data Through Views
- Materialized Views for Caching

### 4.2 Stored Procedures and Functions
- `CREATE FUNCTION` with `PL/pgSQL`
- Input/Output Parameters
- Control Flow in Functions (`IF`, `LOOP`, etc.)
- `CREATE PROCEDURE` (PostgreSQL 11+)

### 4.3 Triggers
- `AFTER INSERT`, `BEFORE UPDATE`, etc.
- Creating and Using Triggers for Auditing, Validation

### 4.4 Transactions
- `BEGIN`, `COMMIT`, `ROLLBACK`
- Savepoints
- ACID Properties

### 4.5 Window Functions
- `ROW_NUMBER()`, `RANK()`, `LEAD()`, `LAG()`
- Partitioning with `OVER()`

---

## **Section 5: JSON & Full Text Search**

### 5.1 Working with JSON and JSONB
- Storing JSON
- Querying JSON fields
- Indexing JSONB

### 5.2 Full Text Search
- Using `to_tsvector`, `to_tsquery`
- Creating full-text indexes
- Ranking search results

---

## **Section 6: PostgreSQL Administration**

### 6.1 User Roles and Permissions
- Creating Users and Roles
- Granting/Revoke Permissions
- Role Inheritance

### 6.2 Backup and Restore
- Using `pg_dump`, `pg_restore`
- SQL dumps vs binary dumps
- Full cluster backups with `pg_basebackup`

### 6.3 Performance Tuning
- Query Execution Plans with `EXPLAIN`
- Vacuuming and Autovacuum
- Connection Pooling (pgBouncer)

---

## **Section 7: Integration with Other Tools**

### 7.1 Python + PostgreSQL
- Using `psycopg2` or `asyncpg`
- Performing CRUD operations from Python
- Using ORMs like SQLAlchemy or Django ORM

### 7.2 PostgreSQL with Other Tools
- Connecting with Node.js, Java, PHP, etc.
- Using PostgreSQL in Docker
- PostgreSQL in cloud (AWS RDS, Google Cloud SQL)

---

## **Section 8: Real-World Projects & Practice**

### 8.1 Project Ideas
- Inventory Management System
- Blog Platform with Comments & Tags
- CRM System with User Roles and Permissions
- Reporting Dashboard with Aggregated Views

### 8.2 Practice SQL Challenges
- LeetCode SQL
- Mode SQL Tutorials
- HackerRank PostgreSQL problems

---

## 📚 Recommended Resources

- **Books:**
  - *PostgreSQL: Up and Running* by Regina Obe
  - *Mastering PostgreSQL in Application Development* by Dimitri Fontaine

- **Websites:**
  - https://www.postgresql.org/docs/
  - https://mode.com/sql-tutorial/
  - https://pgexercises.com/

