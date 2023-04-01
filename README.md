
# Article-01 
In thise Article we are desribed the some Data types and basics SQL statements.


## SQL Documentation 

#### [SQL Documentation->Reference](https://dev.mysql.com/doc/)




## Data types in SQL
### A data type is an attribute that spesifies the type of data that the object can hold: integer data, charecter data, monetary data, date and time data, binary strings and so on.
 * Charecter Strings
 * Numeric
 * Date and time
 * binary

## Basics sql statements
 * Data Defination Language
    * Deals with database schemas and description of how the  data should reside in the database.(Create, Alter, Drop)

* Data Manipulation Language
    * Deals with data manipulation and includes most common sql statements and it is used to store modify retrive delete and update data in database.(select, insert, update, delete)

* Data Control Language
    * Includes commands such as GRANT and mostly concernd with rights permissions and other controls of the database.

* Tracsaction Control Language
    * Deals with transaction within a database.(Commit, Rollback, savepoint)

## Create Database Objects
  * The CRETE DATABASE statements is used to create a ne sql database.

  Systax:- CREATE DATABASE <database-name>

## Create Table Statements
  * The CREATE TABLE statements is used to create a new table in selected database.
  Syntax:- CREATE TABLE <table-name>(
      columnA datatype,
      columnB datatype
  );

## Alter Table Statements
  * Alter tabel is used to:
    * ADD, DELETE, Modify columns from existing table.
    * ADD/DROP constraints on an existing table.
Syntax:-
 * ALTER TABLE <table-name> ADD <column-name> <data-type>
 * ALTER TABLE DROP column <column-name>
 * ALTER TABLE <table-name> ALTER column <column-name> <data-type>
     
## Drop Table Statements
  * The DROP TABLE statements is used to drop a tabel from selected database.
Syntax:-  DROP TABLE <table-name>






## 🕮 Please go through [SQL-Documentation](https://learn.microsoft.com/en-us/sql/t-sql/language-reference?view=sql-server-ver16) more info.
