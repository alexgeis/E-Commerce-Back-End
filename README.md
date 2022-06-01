# (ORM): E-Commerce Back End

## Your Task

Back end for an e-commerce site by modifying starter code. Features a working Express.js API and uses Sequelize to interact with a MySQL database.

## User Story

```md
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
```

## Acceptance Criteria

```md
GIVEN a functional Express.js API
WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
THEN I am able to connect to a database using Sequelize
WHEN I enter schema and seed commands
THEN a development database is created and is seeded with test data
WHEN I enter the command to invoke the application
THEN my server is started and the Sequelize models are synced to the MySQL database
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database
```

## Description

First, I used the database schema file to create my initial database and set up the MySql/Sequelize connections I'd require. Once the connection was confirmed, I created the table models, with column constraints/validations, and seeded the database with the provided seed content.

Next I established associations between the tables and tested my validations/references in MySQL Workbench to ensure viability.

Lastly, after the database was populated, I created the API routes for each required request. After much trial and error I was able to create a demo that's fully shown in the video below. This demo shows all routes and available CRUD operations to the user.

## Deployment

Repo: [E-Commerce Back End](https://github.com/alexgeis/E-Commerce-Back-End)

Walkthrough Video: [E-Commerce Back End Video](https://drive.google.com/file/d/11SJyGsrpTDzEV9nVhrtpi6SIoW7bBP3E/view)
