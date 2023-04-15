# Banking Application Using Python And MYSQL
### About Project : 
Created a Banking Application using Python and MySQL. Data entered by the user are stored in MYSQL database in tabular form.The Best Part of this code is that it is 100 % user friendly because of excess use of exceptional handling.This project is designed for The Bank Staff's to keep the records of their customers. Only authorized Users can have the accessibility to the program. User after Logging in have the support to display all records, and modify it accordingly. If someone is not having Login Id, password he/she could make a new id. Further it can also check overall record of a local customer or full detail of a single a/c as per transactions, create a new record for new customer, Update an old customer record, Delete a record of a customer and Update Loans of the customer.
    
### Requirement :
1. Jupyter Notebook <br>
2. Mysql WorkBeanch<br>
3. Python My SQL Converter : Most Important <br>

### Module Used In python Code :
1. DateTime
2. mysql.Connector

### About Mysql :
1. Database - Databricks
2. host = localhost
3. user=root
4. password=root

UserName is the Primary Key in Bank Table and UserName1 is the Foreign key in Transaction Table.

My Sql Code for Creating Table Bank create table bank(name varchar(30), UserName varchar(30)primary key,password tinytext , Date_of_birth date, address varchar(40),Mobile_Number varchar(30) ,Aadhar_no varchar(30), Balance int);

My Sql code for creating Table Transaction: create table Transaction(credited int , debited int , username1 varchar(20), foreign key(username1) references bank(username));
