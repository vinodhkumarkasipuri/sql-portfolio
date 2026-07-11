# Database Management System (DBMS) Introduction

## Overview

A Database Management System (DBMS) is software that allows users to store, organize, manage, retrieve, and update data efficiently.

Before DBMS, organizations stored data in Flat Files (Text Files). As businesses grew, Flat Files created several challenges such as poor security, data inconsistency, slow retrieval, and limited scalability.

To overcome these limitations, Database Management Systems (DBMS) were introduced.

Today, almost every modern application—including Banking Systems, Railway Reservation Systems, E-commerce Platforms, Hospitals, Social Media, and ERP systems—uses a DBMS.

---

# Why DBMS Was Introduced

Initially, applications developed using programming languages such as **C** and **C++** could process data but could not store it permanently.

To store data, developers used Flat Files (Text Files).

Although Flat Files worked for small applications, they introduced several problems when the amount of data increased.

DBMS was introduced to solve these challenges by providing secure, reliable, and efficient data management.

---

# Flat File System

A Flat File is a simple text file used to store data.

Example:

```
1233  Bhaskar  44  Male    Hyderabad  Delhi    INR 2000  30-Dec-1969  S12 55
1234  Latha    22  Female  Chennai    Kanpur  INR 1200  22-Nov-1969  S01 08
```

In the early days, customer information, railway reservations, banking records, and employee data were stored in Flat Files.

As the data volume increased, managing Flat Files became difficult.

---

# Challenges of Flat Files

## 1. No Security

Anyone can open, edit, or delete the file.

### Example

A customer database stored in a text file can be modified by any user.

---

## 2. Poor Data Integrity

Flat Files cannot validate data.

Example:

```
Age = 500

Gender = Moon

Month = 25
```

Invalid data can easily be stored.

---

## 3. Size Limitation

Flat Files cannot efficiently manage millions of records.

Large files become slow and difficult to maintain.

---

## 4. Complex Data Retrieval

Finding specific information requires writing lengthy C/C++ programs.

Example:

> Calculate total railway ticket sales for December.

Developers had to scan the complete file manually using programming logic.

---

## 5. No Indexing

Flat Files do not maintain indexes.

Finding one customer among millions of records becomes very slow.

---

## 6. Concurrency Issues

Multiple users cannot efficiently access and modify the same file simultaneously.

Example:

Two customers attempting to book the same railway seat at the same time may create inconsistent data.

---

# How DBMS Solves These Problems

| Flat File Problem | DBMS Solution |
|-------------------|---------------|
| No Security | User Authentication & Authorization |
| Poor Data Integrity | Constraints & Validation |
| Limited Storage | Supports Large Databases |
| Slow Retrieval | SQL Queries & Optimization |
| No Indexes | Indexes |
| Concurrency Issues | Transaction Management |

---

# Database Management System (DBMS)

A DBMS is software that provides an organized method to store, retrieve, update, and manage data.

It acts as an interface between users and the database.

Major responsibilities include:

- Data Storage
- Data Retrieval
- Data Security
- Data Integrity
- Backup & Recovery
- Concurrent Access
- Performance Optimization

---

# Types of DBMS

## 1. Network DBMS

Stores data using a network structure.

Status:

Legacy technology.

---

## 2. Hierarchical DBMS

Stores data in a parent-child hierarchy.

Status:

Limited flexibility.

---

## 3. Relational DBMS (RDBMS)

Stores data in tables using rows and columns.

Uses relationships between tables.

Most widely used database model today.

---

# RDBMS

RDBMS stands for **Relational Database Management System**.

It organizes data into related tables.

Features include:

- Primary Keys
- Foreign Keys
- Relationships
- SQL Language
- Constraints
- Transactions
- Indexes
- Multi-user Support

---

# Dr. E. F. Codd

Dr. Edgar F. Codd proposed the Relational Database Model while working at IBM.

He introduced **12 Codd Rules** that define how a relational database should behave.

A database implementing most of these rules is considered an RDBMS.

---

# SQL Language

SQL stands for **Structured Query Language**.

SQL is used to:

- Create Databases
- Create Tables
- Insert Data
- Retrieve Data
- Update Data
- Delete Data
- Manage Security

Unlike C or C++, SQL is specifically designed for working with databases.

---

# Popular RDBMS Software

| Software | Company |
|-----------|----------|
| Oracle Database | Oracle |
| SQL Server | Microsoft |
| DB2 | IBM |
| MySQL | Oracle |
| PostgreSQL | PostgreSQL Global Development Group |
| Teradata | Teradata |

---

# SQL Server History

| Version | Release Year |
|----------|--------------|
| SQL Server 1.0 | 1989 |
| SQL Server 6.0 | 1995 |
| SQL Server 7.0 | 1998 |
| SQL Server 2000 | 2000 |
| SQL Server 2005 | 2005 |
| SQL Server 2008 | 2008 |
| SQL Server 2012 | 2012 |
| SQL Server 2014 | 2014 |
| SQL Server 2016 | 2016 |
| SQL Server 2017 | 2017 |
| SQL Server 2019 | 2019 |
| SQL Server 2022 | 2022 |

---

# Real-World Business Example

## Railway Reservation System

### Before DBMS

- Passenger data stored in Text Files.
- Searching reservations was slow.
- Multiple users caused conflicts.
- Data could be modified without validation.

### After DBMS

- Secure storage.
- Fast retrieval using SQL.
- Concurrent bookings supported.
- Data integrity maintained.
- Backup and recovery available.

---

# Key Differences

| Flat File | DBMS |
|------------|------|
| Low Security | High Security |
| Slow Retrieval | Fast Retrieval |
| No Indexes | Supports Indexes |
| No Relationships | Supports Relationships |
| Poor Integrity | High Integrity |
| Limited Storage | Large Scale Storage |
| Difficult Maintenance | Easy Maintenance |

---

# Key Takeaways

- Flat Files were the earliest method of storing data.
- Flat Files had several limitations.
- DBMS was introduced to overcome these limitations.
- RDBMS became the most successful database model.
- SQL is the standard language used to communicate with relational databases.

---

# Interview Questions

### Beginner

1. What is DBMS?
2. Why was DBMS introduced?
3. What is a Flat File?
4. What are the limitations of Flat Files?
5. What is SQL?
6. What is RDBMS?
7. Name five RDBMS software.
8. Who is Dr. E. F. Codd?
9. What is Data Integrity?
10. What is Concurrency?

### Intermediate

1. Difference between DBMS and RDBMS.
2. Why are indexes important?
3. Explain data integrity with an example.
4. Explain concurrency.
5. What are the advantages of SQL over C language for data retrieval?
6. What are Codd Rules?
7. Why is SQL considered a declarative language?
8. What problems occur in Flat Files?
9. Explain database scalability.
10. Why do modern applications use RDBMS?

---

# Summary

This chapter introduced the fundamentals of Database Management Systems (DBMS), the limitations of Flat File Systems, the evolution of RDBMS, SQL, and the importance of structured data management. These concepts form the foundation for learning SQL and understanding how modern database systems work.

---

# Learning Outcome

After completing this topic, you will be able to:

- Explain why DBMS was introduced.
- Describe the limitations of Flat Files.
- Differentiate DBMS and RDBMS.
- Understand the role of SQL.
- Identify major RDBMS software.
- Explain basic database concepts in interviews with confidence.
