# EXP NO 1: DATA DEFINITION LANGUGE COMMANDS IN RDBMS

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
create table student3( rollno int, name varchar(50), age int, address varchar(50), phoneno varchar(30));


### OUTPUT:
![dbms1 1output](https://github.com/MSowmya28/I2_DBMS/assets/94154791/ade35c1b-680b-4455-948e-972f9669bda2)

### 2) Change the above student table by adding another attribute department

### SQL QUERY: 
 alter table student3 add department varchar(10);

### OUTPUT:

![dbms1 2output](https://github.com/MSowmya28/I2_DBMS/assets/94154791/3d0f712d-cc60-4640-a8e5-461da0ada231)

### 3) Drop the student table
 
### SQL QUERY: 
 drop table student2;


### OUTPUT:
![dbms1 3output](https://github.com/MSowmya28/I2_DBMS/assets/94154791/ad3a8c46-990d-49e4-8cef-ad918c9c6f6f)



### 4) Delete the student table using truncate keyword

### SQL QUERY: 
 truncate table mystudent;


### OUTPUT:

![dbms1 5output](https://github.com/MSowmya28/I2_DBMS/assets/94154791/194000db-3db5-4687-b9af-b1b8ac8c41a8)


### 5) Rename the student table to mystudent

### SQL QUERY: 
rename table student3 to mystudent;

### OUTPUT:
![dbms1 4output](https://github.com/MSowmya28/I2_DBMS/assets/94154791/bbb19b11-e5f8-49b6-91c2-d56e06d8c1e5)
