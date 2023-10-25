# E-Commerce Backend

## Description

This project is a back-end solution for an e-commerce website. Utilizing Express.js and Sequelize, this application interfaces with a MySQL database to manage an online store's inventory.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Tests](#tests)
4. [Questions](#questions)

## Installation

To get started, clone the repository from [GitHub](https://github.com/Trifectice).

Then navigate to the project directory and install the necessary dependencies with the following command:

```bash
npm install
```
Ensure that you have MySQL installed on your machine. Run the schema.sql file in the MySQL shell to set up the database. Then seed the database with the following command:

```bash
npm run seed
```
Create a .env file in the root of the project directory with your MySQL credentials:

DB_NAME='ecommerce_db'
DB_USER='your_username'
DB_PW='your_password'

## Usage

Start the server with the following command:

```bash
npm start
```

Use an API testing tool like Insomnia Core or Postman to interact with the available API endpoints.

## Tests

There are no tests included in this project. However, you can verify the functionality of the API endpoints using an API testing tool.

## Questions
For questions or support, contact [Keller](https://github.com/Trifectice) on GitHub.

