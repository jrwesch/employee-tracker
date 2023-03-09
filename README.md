# Employee Tracker

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Contributors](#contributors)
- [Tests](#tests)
- [Technology Used](#technology-used)
- [Questions](#questions)

## Description
This assignment is to build a command-line application from scratch to manage a company's employee database using Node.js, Inquirer, and MySQL.

## Installation

The user will need to use the [MySQL2 package](https://www.npmjs.com/package/mysql2) to connect to your MySQL database and perform queries, the [Inquirer package](https://www.npmjs.com/package/inquirer/v/8.2.4) to interact with the user via the command line, and the [console.table package](https://www.npmjs.com/package/console.table) to print MySQL rows to the console. If installing through the terminal please ensure you install inquirer version 8.2.4 (npm i inquirer@8.2.4)
 
## Usage
**Acceptance Criteria** </br>
GIVEN a command-line application that accepts user input</br>
WHEN I start the application</br>
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role</br>
WHEN I choose to view all departments</br>
THEN I am presented with a formatted table showing department names and department ids</br>
WHEN I choose to view all roles</br>
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role</br>
WHEN I choose to view all employees</br>
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers </br>
that the employees report to</br>
WHEN I choose to add a department</br>
THEN I am prompted to enter the name of the department and that department is added to the database</br>
WHEN I choose to add a role</br>
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database</br>
WHEN I choose to add an employee</br>
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database</br>
WHEN I choose to update an employee role</br>
THEN I am prompted to select an employee to update and their new role and this information is updated in the database</br>

## Contributors
To contribute to the Employee Tracker, clone this repo locally and commit your code on a separate branch.
  

## Technology Used
- MySQL
- Node.js
- Inquirer

## Questions/Links
Any questions can be directed to me at https://github.com/jrwesch

The repository is found at: https://github.com/jrwesch/employee-tracker
  
[Link to video of demonstration](https://drive.google.com/file/d/1dBDoz3rDCcyRQKZc5VN3VMze5eSdknS8/view)