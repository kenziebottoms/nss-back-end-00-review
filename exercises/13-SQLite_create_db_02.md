# SQLite Practice

In this exercise you will create a SQLite database, create tables, insert records to the table, and query the database. We will be using the npm module [sqlite3](https://www.npmjs.com/package/sqlite3).

## Instructions

A friend of yours owns a small family business and wants to start moving all of their business records into a database. Using your NodeJS skills, they want you to create a SQLite database to store information about their employees.

- [x] Create a database that is saved on disk.
- [x] Create a table titled `employees` with the following columns:
    - [x] id
    - [x] firstName
    - [x] lastName
    - [x] jobTitle
    - [x] address
- [x] Create an array of at least 6 objects. Each object should have a key value pair matching each column name in the `employees` table.
- [x] Insert each of the employee objects into the database.
- [x] Write a statement to query the database and `console.log()` all employee records.
- [x] Write a statement to query the database and `console.log()` each employee's `jobTitle`.
- [x] Write a statement to query the database and `console.log()` each employee's `firstName`, `lastName` and `address` only.

## Bonus Features

- [x] Instead of using an array in the `.js` file, create a `.json` file of employees to require into the `.js` file. Use this to populate the table.
- [ ] Your friend has decided that they want to add a salary column to the employees table. Make sure to add a `salary` key-value pair to each of the employee objects. Then drop the existing employees table, update the schema to accept a salary column, and repopulate the table.
- [ ] Write a statement that returns all employees of a specified `jobTitle`.