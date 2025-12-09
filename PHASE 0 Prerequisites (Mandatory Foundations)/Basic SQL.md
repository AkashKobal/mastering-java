## **Basic SQL**

### **What is SQL?**
**SQL (Structured Query Language)** is a standard programming language specifically designed for managing and manipulating **relational databases**
- It allows users to **create, read, update, and delete data** within a database.
- SQL is widely used in various applications, from **web development to data analysis**, due to its efficiency in handling structured data.
- Widely supported across various database systems like **MySQL, Oracle, PostgreSQL, SQL Server**, and many others.
- Mainly works with **Relational Databases** (**data stored in the form of tables**)

---

### **Key Concepts of SQL:**
1. **Tables:** Data is organized in tables, which consist of **rows and columns**.
2. **Queries:** SQL uses queries to perform operations on the database.
3. **Data Manipulation Language (DML):** Commands like **SELECT, INSERT, UPDATE, DELETE** used to manipulate data.
4. **Data Definition Language (DDL):** Commands like **CREATE, ALTER, DROP** used to define and modify database structures.
5. **Joins:** Used to combine rows from **two or more tables** based on a related column.
6. **Indexes:** Improve the **speed of data retrieval** operations.
7. **Transactions:** Ensure **data integrity** by grouping multiple operations into a single unit of work.
8. **Normalization:** Process of organizing data to **reduce redundancy** and improve data integrity.
9. **Constraints:** Rules applied to table columns to enforce **data integrity** (e.g., **PRIMARY KEY, FOREIGN KEY, UNIQUE, NOT NULL**).
10. **Views:** Virtual tables created by querying data from one or more tables.
11. **Stored Procedures:** Predefined SQL code that can be saved and reused to perform specific tasks.
12. **Functions:** Built-in or user-defined operations that return a **single value** based on input parameters.
13. **Triggers:** Automated actions executed in response to specific events (**INSERT, UPDATE, DELETE**).
14. **Schemas:** Logical containers that group database objects like tables, views, and procedures.
15. **Backup and Recovery:** Mechanisms to **protect data** and restore it in case of loss or corruption.
16. **Security:** Mechanisms to control **access to the database** (user roles, permissions).
17. **Data Types:** Define the type of data stored in a column (e.g., **INTEGER, VARCHAR, DATE**).
18. **Aggregation Functions:** Perform calculations on a set of values (e.g., **COUNT, SUM, AVG, MAX, MIN**).
19. **Subqueries:** Queries nested within another query for complex data retrieval.
20. **CTEs (Common Table Expressions):** Temporary result sets referenced within SQL statements.

---

### **Rules for Writing SQL Queries**
1. **SQL keywords are case-insensitive** (SELECT = select).
2. **Statements must end with a semicolon (`;`)**.
3. Use **single quotes (`' '`)** for string literals.
4. Use **double quotes (`" "`)** for identifiers when needed.
5. **Whitespace allowed:** Queries can span multiple lines.
6. **Reserved words:** Avoid using SQL keywords as names or wrap them in quotes/backticks.
7. **Comments:** Use `--` for single-line and `/* */` for multi-line comments.

---

### **What are Different SQL Commands or Queries?**
SQL commands can be broadly categorized into several types based on their functionality:

1. **Data Query Language (DQL):** SELECT  
   (*Used for reading data in all applications – backend services, dashboards, reports*)

2. **Data Manipulation Language (DML):** INSERT, UPDATE, DELETE, MERGE  
   (*Used for create/update/delete operations in business applications, APIs, microservices*)

3. **Data Definition Language (DDL):** CREATE, ALTER, DROP, TRUNCATE, RENAME  
   (*Used by developers and DBAs to design and modify database schemas*)

4. **Data Control Language (DCL):** GRANT, REVOKE  
   (*Used by DBAs and security teams to manage access control*)

5. **Transaction Control Language (TCL):** COMMIT, ROLLBACK, SAVEPOINT, SET TRANSACTION  
   (*Used in financial systems, order processing, and consistency-critical workflows*)

6. **Session Control Language (SCL):** SET, SHOW, RESET  
   (*Used by applications and DBAs to configure session-level behavior*)

7. **Utility / Diagnostic Commands:** EXPLAIN, DESCRIBE, ANALYZE  
   (*Used by developers and performance engineers for query analysis and optimization*)

8. **Administrative Commands:** BACKUP, RESTORE, VACUUM, CHECKPOINT  
   (*Used by DBAs for database maintenance, recovery, and reliability*)

9. **Analytical / Window Functions:** RANK(), DENSE_RANK(), ROW_NUMBER(), NTILE()  
   (*Used by analytics teams, BI tools, reporting platforms*)

10. **Common Table Expressions (CTEs):** WITH, WITH RECURSIVE  
    (*Used by developers and analysts to write readable, complex queries*)

11. **JSON Commands:** JSON_EXTRACT, JSON_OBJECT, JSON_ARRAYAGG  
    (*Used in modern applications, microservices, and APIs storing semi-structured data*)

12. **Full-Text Search Commands:** MATCH, AGAINST, TSVECTOR  
    (*Used by search-heavy applications, content platforms, e-commerce systems*)

13. **Spatial / GIS Commands:** ST_Contains, ST_Distance, ST_Within  
    (*Used by logistics, ride-sharing, maps, location-based services*)

14. **Temporal Commands:** DATE_ADD, DATE_SUB, INTERVAL  
    (*Used by reporting systems, scheduling apps, time-based analytics*)

15. **Bulk Data Operations:** LOAD DATA INFILE, BULK INSERT, COPY  
    (*Used by organizations for high-volume data imports, ETL pipelines, data warehouses*)

---

### **Benefits of SQL**
1. **Easy to Learn and Use**
2. **Powerful Data Management**
3. **Standardized Language**
4. **Data Integrity**
5. **Scalability**
6. **Integration**
7. **Efficient Data Retrieval**
8. **Flexibility**

---

### **Limitations of SQL**
1. **Complexity with Large Databases**
2. **Performance Issues**
3. **Scalability Concerns**
4. **Platform-Specific Variations**
5. **Lack of Real-Time Analytics**

---

### **Real-World Applications of SQL**
1. **Web Development**
2. **Data Analysis**
3. **Business Intelligence (BI)**
4. **Financial Systems**
5. **Customer Relationship Management (CRM)**
6. **E-commerce**
7. **Healthcare**
8. **Telecommunications**
9. **Education**
10. **Government**

---

### **Conclusion**
**SQL** is a powerful and essential tool for managing **relational databases**. Its efficiency, standardization, and wide adoption make it a **fundamental skill** for developers, analysts, and DBAs. Understanding both its strengths and limitations ensures better **performance, scalability, and reliability** in real-world applications.
