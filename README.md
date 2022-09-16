# SQL-Employee-Tracker

![badge](https://img.shields.io/static/v1?label=license&message=MIT&color=blue)

## Description

Application uses inquirer to build an SQL database that tracks employees, their roles, and their respective departments.

## Table of Contents
- [SQL-Employee-Tracker](#sql-employee-tracker)
  - [Description](#description)
  - [Table of Contents](#table-of-contents)
  - [What to Expect](#what-to-expect)
  - [Walkthrough](#walkthrough)
  - [License](#license)

## What to Expect

When the user runs the application in Terminal:
- The user is presented with the title of the application.
- The user is then presented with a list of options for what they would like to do first.
- Once the user selects the desired action, they are presented with a response based on their selection.
- Selecting "view employees" will present the user with a table of all employees currently in the database.
- Selecting "view roles" will present the user with a table of all roles currently in the database.
- Selecting "view departments" will present the user with a table of all roles currently in the database.
- Selecting "add employee" will present the user with prompts to add the employee accurately.
- Selecting "add role" will present the user with prompts to add a role to the database.
- Selecting "add department" will present the user with prompts to add a department to the database.
- Selecting "update employee" will present the user with a list of employees which they will chose from to update.

## Walkthrough

Theoretically one would install the dependencies using `npm i` and then run the application using `npm server` but for some reason I could not get mysql to run. I tried reinstalling it, deleting my node modules, reinstalling my node modules, installing them globally, uninstalling again, etc. etc. and nothing worked so I was unable to actually run the application. 

Based on the code, once you use `npm server` it will prompt the user to choose from a list of options that lets them interact with the database. Each employee can have a role, and a department assigned. The user can add as many roles and departments as they see fit and then when adding an employee they can assign them roles and departments as well. As things get added to the database they can choose to update the item which will then access it from the database and update it with the new information and store it again. Once done modifying the database, the user can choose to view all the employees/roles/departments at once. 

## License

This application is using MIT.
