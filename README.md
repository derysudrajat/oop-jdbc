# oop-jdbc
Example CRUD local databse in Intellij Idea

## Get Started
Before using this repository i recommended to prepare some material below, you can download it fisrt.

 - [Dowload XAMPP](https://www.apachefriends.org/download.html)
 - [Download Intellij Idea](https://www.jetbrains.com/idea/download/)
 - [Download JDBC Connector](https://github.com/derysudrajat/Madhang/blob/master/lib/mysql-connector-java-8.0.11.jar)

## Create database and table

Create Database db_mahasiswa

```mysql
create database db_mahasiswa
```


Create Table mahasiswa

```mysql
create table mahasiswa (  
    id int not null primary key auto_increment,  
    nama varchar(255),  
    alamat varchar(255),  
    telepon varchar(20)  
)
```
