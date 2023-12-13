# write steps as below and make a document to refer in future
1. write a command to update (sudo apt update)
```bash
sudo apt update
```
2. write a command to upgrade
```bash
sudo apt upgrade
```
3. write a command to install sql server
```bash
sudo apt install mysql-server
```
4. write a command to  install sql client
```bash
sudo apt install mysql-client
```
5. write a command to check my sql version
```bash
mysql --version
```
6. write a command to start mysql
```bash
sudo service mysql start
```
7. write a command to stop mysql
```bash
sudo service mysql stop
```
8. write a command to restart mysql
```bash
sudo service mysql restart
```
9. write a command to start sql editor to write queries
```bash
mysql
```
10. write a command to create database
```bash
CREATE DATABASE name_of_database;
```
11. write a command to create user
```bash
CREATE USER 'user'@'localhost' IDENTIFIED BY 'password';
CREATE USER 'user'@'%' IDENTIFIED BY 'password';
```
12. write a command to grant all permisiion for that user on specific database
```bash
GRANT ALL PRIVILEGES ON database.* TO 'user'@'localhost';
GRANT ALL PRIVILEGES ON database.* TO 'user'@'%';
```
13. write a command to show all grants for specific user
```bash
SHOW GRANTS FOR 'user'@'localhost';
SHOW GRANTS FOR 'user'@'%';
```
14. write a command to create database
```bash
// Same as before:
CREATE DATABASE name_of_database;
```
15. write a command to create table
```bash
CREATE TABLE name_of_table (column1 datatype, column2 datatype, ...);
```   
16. write a command to insert values in table
```bash
INSERT INTO name_of_table (column1, column2, ...) VALUES (value1, value2, ...);
INSERT INTO name_of_table VALUES (value1, value2, ...);
```
17. write a command to display total number of tables
```bash
SHOW TABLES;
```
18. write a command to display total number of databases
```bash
SHOW DATABASES;
```
19. write a command to get all values from particular table
```bash
SELECT * FROM name_of_table;
```
20. write a command to show number of antries
```bash
SELECT COUNT(*) FROM name_of_table;
\\ More specific e.g. email xyz@web.de:
SELECT COUNT('web.de') FROM name_of_table;
```
21. write a command to alter the table
```bash
ALTER TABLE name_of_table ADD COLUMN new_column datatype;
```
    

