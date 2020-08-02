# Employee Tracker
  
  [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
  
  ### Description

   Developers are often tasked with creating interfaces that make it easy for non-developers to view and interact with information stored in databases. Often these interfaces are known as Content Management Systems. This application allows the user to access a database of employees information in their company, the application utlizes Javascript and Node.js to interact with the information stored in a MySQL server. The user is able to freely manipulate the company data by adding information about departments, roles, and employees, updating employee information, and deleting employees from the company database. The employee information is available for the user to view by department or by manager.
  
  ### User Story

  As a business owner
  I want to be able to view and manage the departments, roles, and employees in my company
  So that I can organize and plan my business

  Repository: https://github.com/EMackPierre/Employee-Tracker
  
  ### Table of Contents

  * [Installation](#installation)
  * [Usage](#usage)
  * [Contributors](#contributors)
  * [License](#license)
  * [Tests](#tests)
  * [Questions](#questions)

  ### Installation

  First clone the repository to your local machine. From the command line type "npm install" or "npm i" this will automatically install the required npm packages (inquirer, mysql, figlet) through the info in the package.json file. You can also manually install by running command line "npm install inquirer mysql figlet" which will install all three npm packages. Now click and open up the "app.js" file. Be sure to put in MySQL database password if needed(Line 20 in code). Now from your MySQL workbench input the data from the file "employees_db.sql" inside the "db" folder to create the database with the correct tables and columns. The final step is to run "apps.js" in the command line to begin application. 

  ### Usage

   This command-line application allows the user to:

  * Add departments, roles, employees

  * View departments, roles, employees

  * Update employee roles

  * Update employee managers

  * Delete departments, roles, and employees

The application will be invoked with the following command:

                node app.js

  ### App video example

  [Video Link App Working]()

  ### App Screen Shots

  ![Photo]()   
  ![Photo]()

  ### Contributors

  None

  ### License

  Click on the badge at the top of the file to learn more about the license.

  ### Tests

  None

  ### Questions

  If you have any additional questions you may contact me at https://github.com/EMackPierre

  You may also email me at emmp318@gmail.com