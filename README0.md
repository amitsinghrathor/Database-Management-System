# python-tkinter-mysql-project-car-rental

# DBMS Code

mysql> create database dbmsproject ;
Query OK, 1 row affected (0.01 sec)

mysql> use dbmsproject ;
Database changed
mysql> create table cars ( car_id int primary key, brand char(20), rent int, available char(5) ) ;
Query OK, 0 rows affected (0.04 sec)

mysql> create table users ( user_id int primary key auto_increment , name char(20), email char(20), startdate date, loc char(20) ) ;
Query OK, 0 rows affected (0.02 sec)

mysql> create table manages (user_id int, car_id int) ;
Query OK, 0 rows affected (0.02 sec)

mysql> create table admin(username char(20) primary key, password char(20) ) ;
Query OK, 0 rows affected (0.02 sec)