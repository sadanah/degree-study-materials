# Database Design and Development

Technologies used: MySQL, XAMPP or WAMP Server

- [XAMPP Server](https://sourceforge.net/projects/xampp/)
- [WAMP Server](https://sourceforge.net/projects/wampserver/)

## Contents

1. DAD Principles
2. Basic SQL queries 
3. CRUD Operations
4. Create
5. Read
6. Update 
7. Delete
8. SQL Join Functions
9. Q & A


## 1. DAD Principles


## 2. Basic SQL Queries 

2.1 Getting Started

After setting up XAMPP/WAMP Server, you can proceed to interact with database using SQL commands and queries.

This is usually the default command to start the MySQL client:

```bash
mysql -h localhost -u root -p
````


2.2 Using Databases

View Available Databases: 
```bash
SHOW DATABASES;
````

Create New Databases: 
```bash
CREATE DATABASE dbname;  //dbname = name of your database
USE dbname;
SELECT DATABASE();
````

Delete Existing Databases: 
```bash
DROP DATABASE dbname;
````


## 3. CRUD Operations

CRUD Operations (Create, Read, Update, Delete) form the basis of database interactions. 

## 4. Create

4.1 Create Table: 
```bash
//replace tablename with your table name, and tableCol with each column name

CREATE TABLE tablename(
  -> tableCol1 INT(10) PRIMARY KEY,    // this feild is the primary key which is an integer value of size 10
  -> tableCol2 INT(10),                // this field has the same type and size of a foreign key (later declared as foreign key constraint)
  -> tableCol3 VARCHAR(100),           // variable character field with size 100 chatacters
  -> tableCol4 VARCHAR(255));
````


## 5. Read

5.1 DESCRIBE 

To view table fields with their properties (i.e. data type, size, constraints)
```bash
DESCRIBE tablename;
````
```bash
//OUTPUT

--
````

5.2 SELECT

SELECT can be used to query the database for specific information.

```bash
//To select ALL records from a table

SELECT * FROM tablename;
````

```bash
//To select all records with 

SELECT * FROM tablename;
````

## 6. Update


## 7. Delete


## 8. SQL Join Functions


## 9. Q & A
