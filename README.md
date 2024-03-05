# EcoTech-Ecommerce-Backend
## Overview
 This repository hosts the backend code for EcoTech-Ecommerce-Backend, a cutting-edge back-end solution for internet retail companies specializing in electronic products. Built on Express.js and leveraging Sequelize for ORM with a MySQL database, it enables seamless e-commerce operations by facilitating CRUD operations on categories, products, and tags through a well-defined API. The project is designed to meet the demands of modern e-commerce platforms, ensuring high scalability, robust data management, and a developer-friendly environment for further enhancements.


## Table of Contents
1. [Overview](#overview)
2. [User Story](#user-story)
3. [Acceptance Criteria](#acceptance-criteria)
4. [Installation](#installation)
5. [Usage](#usage)
6. [Features](#features)
7. [Technologies Used](#technologies-used)
8. [Screenshot](#screenshot)
9. [Deployed Application](#deployed-application)
10. [License](#license)
11. [Collaborators](#collaborators)
12. [Code Attribution](#code-attribution)
13. [External Resources](#external-resources)
14. [Credits](#credits)


## User Story
- AS A manager at an internet retail company,
- I WANT a back end for my e-commerce website that uses the latest technologies
- SO THAT my company can compete with other e-commerce companies


## Acceptance Criteria
GIVEN a functional Express.js API

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


## Installation
To install necessary dependencies, run the following command:

npm install


## Usage
To start the server, run:

npm start

To seed the database, run:

npm run seed


## Features
- CRUD operations for managing products, categories, and tags.
- Database seeding for initial data setup.
- Environment variable integration for database configuration.

## Technologies Used
- Node.js
- Express.js
- MySQL
- Sequelize ORM
- dotenv

## Screenshot
N/A

## Deployed Application
This application is not deployed since it's a backend service. Please refer to the installation and usage sections to run it locally.

## License
This project is licensed under the [MIT license](LICENSE).

## Collaborators
- [Kyle Huff](https://github.com/Kykesh)

## Code Attribution
- This project was inspired by © 2024 edX Boot Camps LLC

## External Resources
- [Sequelize Documentation](https://sequelize.org/)
- [Express.js Documentation](https://expressjs.com/)

## Credits
© 2024 edX Boot Camps LLC. Starter code provided by edX Boot Camps.

