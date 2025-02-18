# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS
## DATE:
## AIM:
To create a student database and execute DDL queries using SQL.


## DDL (Data Definition Language)
<div align="justify">
DDL or Data Definition Language actually consists of the SQL commands that can be used to define the database schema. It simply deals with descriptions of the database schema and is used to create and modify the structure of database objects in the database. DDL is a set of SQL commands used to create, modify, and delete database structures but not data. These commands are normally not used by a general user, who should be accessing the database via an application.
</div>
 
## List of DDL commands: 
<div align="justify">
CREATE: This command is used to create the database or its objects (like table, index, function, views, store procedure, and triggers).
DROP: This command is used to delete objects from the database.
ALTER: This is used to alter the structure of the database.
TRUNCATE: This is used to remove all records from a table, including all spaces allocated for the records are removed.
RENAME: This is used to rename an object existing in the database.
</div>

## Query:
### 1) Create a table student with the following fieds rollno,name,age,address,phoneno.

### SQL QUERY: 
```
create table student(rollno int,name char(20),age int,addr varchar(20),phoneno int);

```
### OUTPUT:

![image](https://github.com/Revathi-Dayalan/F2_DBMS/assets/96000574/ada9f5e4-be8d-47bb-9413-160bf7a9b360)


### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
```
alter table student add department char(30);
```
### OUTPUT:

![image](https://github.com/Revathi-Dayalan/F2_DBMS/assets/96000574/d0d32a0e-23f6-4d81-9847-0cc9f6dea95b)


### 3) Drop the student table
 
### SQL QUERY: 
```
drop table student;

```


### OUTPUT:

![image](https://github.com/Thenmozhi-Palanisamy/F2_DBMS/assets/95198708/a7bbf8c3-edb8-4c94-88c2-f16e78cbb3f4)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 

```
truncate table student;
````


### OUTPUT:


![image](https://github.com/Revathi-Dayalan/F2_DBMS/assets/96000574/d22e8c89-3f7e-49ef-8bf8-4566706f8e4c)


### 5) Rename the student table to mystudent

### SQL QUERY: 

```
alter table student rename to mystudent;

````
### OUTPUT:


![image](https://github.com/Revathi-Dayalan/F2_DBMS/assets/96000574/b276afdf-c9bc-438b-bf9f-db992a878e63)

## Reslt:
To create a student database and execute DDL queries using SQL is executed successfully.

