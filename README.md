# E-commerce Back End

## User Story: 
#### AS A manager at an internet retail company
#### I WANT a back end for my e-commerce website that uses the latest technologies
#### SO THAT my company can compete with other e-commerce companies

## Acceptance Criteria:
#### GIVEN a functional Express.js API
#### WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
#### THEN I am able to connect to a database using Sequelize
#### WHEN I enter schema and seed commands
#### THEN a development database is created and is seeded with test data
#### WHEN I enter the command to invoke the application
#### THEN my server is started and the Sequelize models are synced to the MySQL database
#### WHEN I open API GET routes in Insomnia Core for categories, products, or tags
#### THEN the data for each of these routes is displayed in a formatted JSON
#### WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
#### THEN I am able to successfully create, update, and delete data in my database

  ## License:   
  ### MIT

  ## Table of Contents
  ### * [Description](#description)
  ### * [Installation](#installation)
  ### * [Usage](#usage)
  ### * [Contributing](#Contributing)
  ### * [Tests](#tests)
  ### * [Questions](#questions)

  ## Description
  #### This application is the back end of an e-commerce site. Express.js API is configured to use Sequelize to interact with a MySQL database.

  ## Installation
  #### Clone the repository. Node.js and MySQL needs to be installed in your computer. Once the repository is cloned, install dependencies.
  #### This is done by running the following in your terminal:
  #### npm install express
  #### npm install sequelize
  #### npm install mysql2
  #### npm install dotenv

  ## Usage
  #### Upon installing the dependencies, you will also need to place a .env file in the root directory of the project in order to connect to your MySQL database. Example:
      DB_NAME=library_db
      DB_PASSWORD=
      DB_USER=root

  #### Run the following commands in your terminal:
      1. mysql -u root -p
      2. source db/schema.sql
      3. quit
      4. npm run seed
      5. npm start


  ## Contributing
  ### Please refer to contact details if you would like to contribute to the project.

  ## Tests
  ### N/A

  ## Questions
  ### If you have any questions, contact me at

  ### GitHub: https://github.com/https://github.com/romeocd
  ### Email: rdumlao07@gmail.com

  ## Video Demonstration
  #### Part 1: (Terminal)
  https://drive.google.com/file/d/1IniePDsScCPlhnRxI-7evVULJ-u7sE2K/view

  #### Part 2: (Insomnia)
  https://drive.google.com/file/d/1c9IzqsYJg2obSlGL0PBWbyIsjR7Vdge1/view
  


  
