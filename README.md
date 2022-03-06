# E-Commerce-ORM

### Table of Contents

## Description
The purpose of this project is to create the back-end for an e-commerce company.
The back-end consists of a database accessed by javascript (ORM principle) and
the database will contain data concerning products, categories, tags, and 
product tags. 

## Project Files
- config directory (used to handle the sequelize connection to the database)
- db directory (location of the sql file: schema.sql)
- models directory (location of js files used as blueprints for 
the category, product, product tag, and tag model)
- routes directory (location of files used to organize the routes for each model)
- seeds directory (location of files used to add data to the database)
- server.js (the main file for connecting to the database and express)
- .env (file to hide mysql login info)
- .gitignore
- node_modules and package.json/package-lock.json (files necessary to make everything work)
- this readme file

### Additional Libraries and Packages
- Express Package (used to connect to a server)
- Mysql2 Package (used to maniplate database)
- Sequelize Package (used as middleware between mysql and javascript)
- Dotenv Package (used to store mysql login info)

## Contributors
Made by Michael Brown (aka randomguy1234)
