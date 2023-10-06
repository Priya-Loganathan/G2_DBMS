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
```
create table student_table1(Roll_no numeric(10) , Name varchar(20) , Age numeric(3), Address varchar(20) , Phone_no numeric(10));
Inserting rows
```
query : insert into student_table1 values ( 1,'Priya',18,'Nerkundram',7845921709);
### OUTPUT:
![image](https://github.com/Priya-Loganathan/G2_DBMS/assets/121166075/f1e8b510-6ff6-433a-9438-74b222afa0f6)
![image](https://github.com/Priya-Loganathan/G2_DBMS/assets/121166075/74ed60f9-b51a-4aa1-adc5-f78adfaebc43)
![image](https://github.com/Priya-Loganathan/G2_DBMS/assets/121166075/56192d17-1ae6-4b9a-b959-18ed26869c68)

### 2) Change the above student table by adding another attribute department
### SQL QUERY: 
alter table student_table1 add Email varchar(100);
### OUTPUT:
![image](https://github.com/Priya-Loganathan/G2_DBMS/assets/121166075/02eead39-8862-48c3-9795-12ca99b81b12)

### 3) Drop the student table
### SQL QUERY: 
Drop table student_tabel;
### OUTPUT:
![image](https://github.com/Priya-Loganathan/G2_DBMS/assets/121166075/08f71a5c-f8e1-4b72-81b3-87d499f1b18b)

### 4) Delete the student table using truncate keyword
### SQL QUERY: 
Truncate table student_table1;
### OUTPUT:
![image](https://github.com/Priya-Loganathan/G2_DBMS/assets/121166075/0c7c590a-f926-4aca-8a29-beba5d138bd6)

### 5) Rename the student table to mystudent
### SQL QUERY: 
alter table student_table1 rename to mystudent;
### OUTPUT:
![image](https://github.com/Priya-Loganathan/G2_DBMS/assets/121166075/2efb9de4-a470-4bd4-a8ce-351ec4cb28a1)

### RESULT:
Thus , a student database is created and DDL queries are executed in SQL.
