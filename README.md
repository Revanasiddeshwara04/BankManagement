# BankManagement
Steps to execute project in your laptop/computer
1)download all the project and open it on your intellij
2)Need to add the jar files Jcalander jar and mysql connector jar which are available with this BankManagement Project/ you can download it from google =>just type "Jcalander jar" and download it from => "toedter" and for "mysql-connector-java-8.0.28.jar" type this in google for mysql connector and download.
3) for adding jar files in intellij open ->File, Goto->Project Structure =>Libraries=>in this libraries there will be   "+"    Sign click on that add open the jar source and click okay.
now u need to create database in "mysql-workbench", if u dont have mysql download it and watch how to install it.
create tables like => 1) create database BankSystem;
2) use BankSystem;
3) create table login(formno varchar(30),cardnumber varchar(30),pin varchar(10));
4) create table login(formno varchar(30),name varchar(30),fname varchar(30),dob varchar(30) ,gender varchar(30),Email varchar(30),married varchar(30),AddressText1 varchar(30) ,CityText1 varchar (30),StateText1 varchar(30),PinText1 vatchar(30));

5) create table signuptwo(formno varchar(30),sreligion varchar(30),scategory varchar(30),sincome varchar(30),seducation varchar(30),soccupation varchar(30),span varchar(30),saadhar varchar(30),sseniorcitizen varchar(30),sExisting varchar(30));
6) create table signup3(formno varchar(40),accountype varchar(40),cardnumber varchar(25),pin varchar(10),facility varchar(100));
7) create table bank(pin varchar(10),date varchar(50),type varchar(30),amount varchar(30));

8) just check the "root name" and  "password" of your mysql and update it in "Con" class in the project
9) project is ready to execute before that place "icon file" in src.

10) for login page  use first click on the signup after that goto my sql and type "select * from login;" 
