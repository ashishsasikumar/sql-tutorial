
# Create Database and Tables

## Create Database
To create a database in MySQL you can use thew following SQL command.  In this example the database is called tus

```sql
CREATE Database tus
```

The tus database is sample college db to admin students to courses

## Create Tables

Create tables to support administration for users logging in, modules, students and the student registrations for a module

### User Table

A user has a username, email, password, first name, last name and we note the date the record was created.

For a primary key a AI (Auto incrementing) int is chosen.

```sql
CREATE TABLE `tus`.`user` (
  `id` INT NOT NULL AUTO_INCREMENT,
  `username` VARCHAR(16) NOT NULL,
  `email` VARCHAR(255) NOT NULL,
  `password` VARCHAR(32) NOT NULL,
  `create_time` TIMESTAMP NOT NULL DEFAULT CURRENT_TIMESTAMP,
  `firstname` VARCHAR(45) NOT NULL,
  `lastname` VARCHAR(45) NOT NULL,
  PRIMARY KEY (`id`),
  UNIQUE INDEX `username_UNIQUE` (`username` ASC) VISIBLE,
  UNIQUE INDEX `email_UNIQUE` (`email` ASC) VISIBLE);
```