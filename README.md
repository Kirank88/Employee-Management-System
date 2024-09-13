
---------------------------------------------------
Database Queries for EMPLOYEE MANAGEMENT SYSTEM Project
---------------------------------------------------


1 - Create database with in mysql

create database employeemanagementsystem;

2 - Use the database you just created

use employeemanagementsystem;

3 - create login table

create table login(username varchar(20), password varchar(20));

4 - Insert values in login table

insert into login values('admin', '12345');

5 - Create an employee table

create table employee(name varchar(20), fname varchar(20), dob varchar(30), salary varchar(20), address varchar(100), phone varchar(20), email varchar(40), education varchar(20), designation varchar(30), aadhar varchar(25), empId varchar(15));
