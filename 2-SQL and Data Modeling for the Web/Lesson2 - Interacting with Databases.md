# Lesson 2: Interacting with Databases

## 1. Lesson Overview
Topics covered in this lesson:
### 1. Interacting with a (remote) databasee
we'll need to use a Database Management System (DBMS): a software that allows you to interact with a database -> PostgreSQL
### 2. Database Application Programming Interfaces (DBAPIs)
used to interact with a database from another languagee

### 3. psycopg2
- a widely used library
- allows to interact with a database from Python
- is a database adapter that allows to interact with a Postgres database from Python
<br><br><br>


## 2. Relational Databases
- database
- database system
- properties of databases:
    - **persistence:** allow to access later
    - **shared source of truth:** accessible by many users
    - **ability to store many types of data:** efficiently
    - **concurrency control:** handling multiple db actions at once
- database management systems
    - relational
        - PostgreSQL
        - MySQL
        - Oracle
        - SQL Server
        - SQLite
    - nonrelational (noSQL)
        - document stores: mongoDB
        - object databases: perst
        - column stores: cassandra
        - graph databases: neo4j
<br><br>

### Relational Databases
- all data is stored in *tables*
- every table is characterized by a list of *columns* with *data types* por column, and its sets of *data* (organized in rows)
- comes with rules for enforcing *data integrity*, such as *constraints* and *triggers*
<br><br>

### Resources
[Course: Intro to Relational Databases](https://www.udacity.com/course/intro-to-relational-databases--ud197)

[video: An Introduction to Relational Databases](https://www.youtube.com/watch?v=z2kbsG8zsLM)
<br><br>

### Question 1
<p align="center">
  <img src="https://github.com/cintia-shinoda/udacity_full-stack-web-dev-nanodegree/blob/master/images/q-2-2-1.png" alt="q1"/>
</p>
<br>
<br><br>

### Question 2
<p align="center">
  <img src="https://github.com/cintia-shinoda/udacity_full-stack-web-dev-nanodegree/blob/master/images/q-2-2-2.png" alt="q2"/>
<br><br><br>


## 3. Primary Keys & Foreign Keys
### Primary Key
- unique identifier
- *composite key*

### Foreign Key
- primary key in another (foreign) table
- used to map relationships between tables

### Question 1
<p align="center">
  <img src="https://github.com/cintia-shinoda/udacity_full-stack-web-dev-nanodegree/blob/master/images/q-2-3-1.png" alt="q1"/>
<br><br>

### Question 2
<p align="center">
  <img src="https://github.com/cintia-shinoda/udacity_full-stack-web-dev-nanodegree/blob/master/images/q-2-3-2.png" alt="q2"/>
<br><br><br>


## 4. SQL
- SQL: Structured Query Language
- dialects
<br><br>

### SQL Review
Manipulating Data | Querying Data | Structuring Data | Joins & Groupings |
---|---|---|---|
INSERT | SELECT | CREATE TABLE | (INNER) JOIN |
UPDATE | | ALTER TABLE | LEFT JOIN |
DELETE | | DROP TABLE | RIGHT JOIN
| | |ADD COLUMN | GROUP BY |
||| DROP COLUMN | SUM |
||||COUNT  |
<br><br>

### Question 1
<p align="center">
  <img src="https://github.com/cintia-shinoda/udacity_full-stack-web-dev-nanodegree/blob/master/images/q-2-4-1.png" alt="q1"/>
<br><br>

### Question 2
<p align="center">
  <img src="https://github.com/cintia-shinoda/udacity_full-stack-web-dev-nanodegree/blob/master/images/q-2-4-2.png" alt="q2"/>
<br><br>

### Question 3
<p align="center">
  <img src="https://github.com/cintia-shinoda/udacity_full-stack-web-dev-nanodegree/blob/master/images/q-2-4-3.png" alt="q3"/>
<br><br><br>


## 5. Execution Plan


