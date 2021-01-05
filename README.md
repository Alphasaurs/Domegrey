# Domegrey

NOTE:-
Use UPPERCASE for sql query it is not case sensitive but for ease use it \
semi-colon at end 

`psql --version`\
`psql -U postgres` where postgres is a username\
`CREATE DATABASE school;` new database \
`\c database_name` to connect to that database\
`DROP DATABASE school;` delete whole db\

`\dt`to see all table\
`\d table_name` to see that table\
`CREATE TABLE student(id INT,name VARCHAR(10));` create table \
`CREATE TABLE students2(id INT NOT NULL PRIMARY KEY,name VARCHAR(10) NOT NULL);` table with constraints\
`DROP TABLE students;` delete whole table\
`INSERT INTO student (name, date_of_birth) VALUES ('cool', date '2012-12-21');` insert into table\
`SELECT * FROM student;` show table\
