# Module 13 Challenge E-Commerce (ORM)

This uses an Express.js API and configures it to use Sequelize to interact with a MySQL database.

## Tools
- Express.js

- MySQL2

- Insomnia

- Sequelize

## Description

### User Story

AS A manager at an internet retail company

I WANT a back end for my e-commerce website that uses the latest technologies

SO THAT my company can compete with other e-commerce companies

### Acceptance Criteria

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

## Installation 
First, clone the repository from GitHub. This application requires Node.js, Express.js, and Sequelize. To connect to the database run `mysql -u root -p` and enter password from .env file. Then source the schema.sql. To seed the file run `npm run seed`. Lastly, connect to the server by running `npm start`. 

## Usage 
This application will allow users to view, add, edit, and delete categories, products, and tags.

file:///Users/mosby/Downloads/walkthroug.video%20(1).webm

