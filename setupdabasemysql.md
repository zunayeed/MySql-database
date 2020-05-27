- To create database named mydate:    __mysql> create database mydate ;__ // semicolon is a must 
- To connect database:  __mysql> use mydate ;__
                      __mysql> connect mydate ;__ 
// once in mydate, table can be created or drop

- To show or list all databases :   __mysql> show databases;__ 

- To drop a database:  mysql> drop database <database_name>
- To create table: create table employees((eno int(5) primary key,ename varchar(20),esal double(10,2),eaddr varchar(20));
- insert into employees values(100,"Zinia", 1000, "Dhaka,Bangladesh");
- insert into employees values(200,"Zunayeed", 2000, "Indiana,USA");
- insert into employees values(300,"Nusrat", 3000, "Dhaka,Bangladesh");
- insert into employees values(400,"Mostafa", 4000, "Dhaka,Bangladesh");
- insert into employees values(500,"Parvin", 4000, "Dhaka,Bangladesh");
 
##  Order By clause: 
- When you use the SELECT statement to query data from a table, the result set is not sorted. It means that the rows in the result set can be in any order. To sort the result set, you add the ORDER BY clause to the SELECT statement. The following illustrates the syntax of the ORDER BY  clause:
```
SELECT 
   select_list
FROM 
   table_name
ORDER BY 
   column1 [ASC|DESC], 
   column2 [ASC|DESC],
   ...;
   ```
- By default, the ORDER BY clause uses ASC if you don’t explicitly specify any option.
