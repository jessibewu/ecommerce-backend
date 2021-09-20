# E-commerce Backend

![badge](https://img.shields.io/badge/license-MIT-brightgreen)

  ## Description
  Acceptance Criteria:
  
 - GIVEN a functional Express.js API
 - WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
 - THEN I am able to connect to a database using Sequelize
 - WHEN I enter schema and seed commands
 - THEN a development database is created and is seeded with test data
 - WHEN I enter the command to invoke the application
 - THEN my server is started and the Sequelize models are synced to the MySQL database
 - WHEN I open API GET routes in Insomnia Core for categories, products, or tags
 - THEN the data for each of these routes is displayed in a formatted JSON
 - WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
 - THEN I am able to successfully create, update, and delete data in my database

  ## Table of Contents
  - [Description](#description)
  - [Installation](#installation)
  - [Usage](#usage)
  - [License](#license)
  - [Credits](#credits)
  ## Installation
  `npm init`
  `npm i dotenv express mysql2 sequelize`

  ## Usage
  Run `npm run seed` to seed data to your database.
  Then run `node server.js` or `npm start` command at the root of the file to connect to the MySQL database on server start.

  Demo Video:

  - Full youtube video can be viewed [here](https://youtu.be/Zqm2mlsYrYY).
  
  ## License
  This application is covered by [MIT](https://opensource.org/licenses/MIT) license. 
  
  ## Credits: 
  https://courses.bootcampspot.com/