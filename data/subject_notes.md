# Subject: Database Management Systems (B.Tech CSE Core)

## Topic 1: DBMS and File System

A Database Management System (DBMS) is software that allows users to create, store, manage, and retrieve data efficiently. Unlike traditional file systems, a DBMS provides structured data storage, reduces data redundancy, maintains data consistency, and offers better security. It acts as an interface between users and the database.

The main advantages of DBMS include data independence, concurrency control, backup and recovery, data integrity, and controlled access. Popular examples of DBMS software include MySQL, PostgreSQL, Oracle Database, and Microsoft SQL Server.

## Topic 2: Normalization and Normal Forms

Normalization is the process of organizing database tables to minimize data redundancy and prevent insertion, deletion, and update anomalies. It divides large tables into smaller related tables while maintaining relationships through primary and foreign keys.

The major normal forms are:

1. First Normal Form (1NF): Each column must contain atomic (single) values, and repeating groups are not allowed.
2. Second Normal Form (2NF): The table must be in 1NF, and every non-key attribute must be fully dependent on the entire candidate key.
3. Third Normal Form (3NF): The table must be in 2NF and must not contain transitive dependencies between non-key attributes.
4. Boyce-Codd Normal Form (BCNF): Every determinant must be a super key.

Normalization improves database consistency and makes data easier to maintain.

## Topic 3: SQL and Its Types

Structured Query Language (SQL) is a standard programming language used to communicate with relational database management systems. It allows users to create database structures, insert records, retrieve information, modify existing data, and control access permissions.

SQL commands are classified into five major categories:

1. DDL (Data Definition Language): Defines database structures. Examples: `CREATE`, `ALTER`, `DROP`, `TRUNCATE`.
2. DML (Data Manipulation Language): Modifies database records. Examples: `INSERT`, `UPDATE`, `DELETE`.
3. DQL (Data Query Language): Retrieves data from tables. Example: `SELECT`.
4. DCL (Data Control Language): Controls database permissions. Examples: `GRANT`, `REVOKE`.
5. TCL (Transaction Control Language): Manages transactions. Examples: `COMMIT`, `ROLLBACK`, `SAVEPOINT`.

SQL is widely used in web applications, banking systems, enterprise software, and data analytics.

## Topic 4: ACID Properties and Database Transactions

A transaction is a logical unit of work performed on a database. It may consist of multiple operations, such as transferring money from one bank account to another. DBMS uses ACID properties to ensure reliable and consistent transaction processing.

The four ACID properties are:

1. Atomicity: A transaction is completed entirely or not executed at all. Partial transactions are not allowed.
2. Consistency: A transaction must maintain database integrity constraints and move the database from one valid state to another.
3. Isolation: Concurrent transactions should execute without interfering with one another.
4. Durability: Once a transaction is committed, its changes remain permanently stored, even after a system crash.

ACID properties are essential for maintaining reliability in banking, e-commerce, reservation systems, and other applications involving critical data.