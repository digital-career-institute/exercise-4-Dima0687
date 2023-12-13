# write steps as below and make a document to refer in future
1. write a command to update (sudo apt update)
```bash
sudo apt update
```
3. write a command to upgrade
```bash
sudo apt upgrade
```
5. write a command to install sql server
```bash
sudo apt install mysql-server
```
7. write a command to  install sql client
```bash
sudo apt install mysql-client
```
9. write a command to check my sql version
```bash
mysql --version
```
11. write a command to start mysql
```bash
sudo service mysql start
```
13. write a command to stop mysql
```bash
sudo service mysql stop
```
15. write a command to restart mysql
```bash
sudo service mysql restart
```
17. write a command to start sql editor to write queries
```bash
mysql
```
19. write a command to create database
```bash
CREATE DATABASE name_of_database;
```
21. write a command to create user
```bash
CREATE USER 'user'@'localhost' IDENTIFIED BY 'password';
CREATE USER 'user'@'%' IDENTIFIED BY 'password';
```
23. write a command to grant all permisiion for that user on specific database
```bash
GRANT ALL PRIVILEGES ON database.* TO 'user'@'localhost';
GRANT ALL PRIVILEGES ON database.* TO 'user'@'%';
```
25. write a command to show all grants for specific user
```bash
SHOW GRANTS FOR 'user'@'localhost';
SHOW GRANTS FOR 'user'@'%';
```
27. write a command to create database
```bash
// Same as befor:
CREATE DATABASE name_of_database;
```
29. write a command to create table
```bash
CREATE TABLE name_of_table (column1 datatype, column2 datatype, ...);
```   
31. write a command to insert values in table
```bash
INSERT INTO name_of_table (column1, column2, ...) VALUES (value1, value2, ...);
INSERT INTO name_of_table VALUES (value1, value2, ...);
```
33. write a command to display total number of tables
```bash
SHOW TABLES;
```
35. write a command to display total number of databases
```bash
SHOW DATABASES;
```
37. write a command to get all values from particular table
```bash
SELECT * FROM name_of_table;
```
39. write a command to show number of antries
```bash
SELECT COUNT(*) FROM name_of_table;
\\ More specific e.g. email xyz@web.de:
SELECT COUNT('web.de') FROM name_of_table;
```
41. write a command to alter the table
```bash
ALTER TABLE name_of_table ADD COLUMN new_column datatype;
```
    

