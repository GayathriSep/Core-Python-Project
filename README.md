![Screenshot]( https://copyassignment.com/wp-content/uploads/2022/06/Employee-Management-System-Project-in-Python-675x506.jpg )   
 # Employee Management System                       
                                                                                                                                                       
## Introduction
The Employee Management System Project in Python will be a beginner-friendly Python project that will educate students on how to construct console-based Python applications. We will provide you with the whole source code for the Python project so that you can immediately install it on your PC and begin learning.

Employee Management System Python project assists in the automation of manual operations, saving both time and money. This system protects the professional and personal information of employees and the company. This project can be very helpful if you are creating a final-year project in Python.

This Employee Management System in Python with MySQL database is constructed using the Jupyter Notebook in the Python Programming Language. This Simple Project was developed using console-based programming and is linked to a MySQL database as the system’s back-end.

To build an Employee Management System in Python with source code we have to connect the MySQL database to our program, for that, we need to install some Packages.

## Table Of Contents
1. Introduction
Project Overview: Employee Management System Project in Python
2. Installing Packages
3. Code Flow:
3.1 Creating a database in MySQL “emp”
3.2 Creating a Table in MySQL
3.3 Add Employee to employee management system project python
3.4 Check Employee in employee management system project python
3.5 Display Employee function to python employee management system
3.6 To Promote Employees in python project on employee management system
3.7 Remove Employee from employee management system in python with database
3.8 Menu Function of employee management system using python
3.9 Complete Source Code for Employee Management System Project in Python is displayed in .ipynb file format
3.10 Output for Employee Management System Project in Python is uploaded as video

## Installing Packages

To install the mysql-connector-python package, type the following command:

pip install mysqlconnector

In order to develop an Employee Management System in Python with source code that uses MySQL database, we must connect Python to MySQL.

## Code Flow
### Add Employee function:
The Add Employee function will ask for the Employee Id and uses the check employee function to check whether the employee to be added already exist in our record or not if employee details do not already exist then it asks for details of the employee to be added like Employee Name, Post of Employee and Salary of the employee. Now after getting all such details from the user of that system it simply inserts the information in our Employee details table.

### Promote Employee Function:
The Promote Employee function will ask for the Employee Id and uses the check employee function to check whether the employee to be Promoted exist in our record or not if employee details exist then it will ask for the amount by which his salary is to be increased. After getting the valid details it increases the salary of the employee with the given id by the given amount. Remove Employee Function: The Remove Employee Function will simply ask for Id of the employee to be removed because Id is Primary key in our Employee Details Record as there can be two employees with the same name, but they must have a unique id.

### Remove Employee function:
It uses the check employee function to check whether the employee to be removed exists in our record or not if employee details exist then after getting a valid employee id it deletes the record corresponding to that employee id.

### Check Employee Function:
The check employee function takes employee id as a parameter and checks whether any employee with given id exists in the employee details record or not. For checking this it uses cursor.rowcount() function which counts the number of rows that match with given details

## Conclusion
Using these functions used in this project we can able to extract the details of the employees in organization which will be helpful.
 









 



 



