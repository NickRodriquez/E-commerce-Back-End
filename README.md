# E-commerce-Back-End

# Project

This weeks challenge was to build a back end for the e commerce website. I will be using Express.js API to configure it to use sequelize that will interact with the MySQL database. 

I have created a video that will give the visual to show the functionality and display all of the criteria.

# Running Program 
- NPM Install
- NPM Install Dotenv
- NPM Install Express
- NPM Install mysql2
- NPM Install Sequelize
- mysql -u root -p ( this pulls the database up from MYSQL )
- npm run seeds
- node server.js

# User Story 

AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies

# Acceptance Criteria

GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia Core for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia Core
THEN I am able to successfully create, update, and delete data in my database
