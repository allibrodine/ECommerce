# E-commerce Back End

[![License: ISC](https://img.shields.io/badge/License-ISC-blue.svg)](https://opensource.org/licenses/ISC)

## Table of Contents

- [Project Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Collaboration](#collaboration)
- [License](#license)
- [Questions](#questions)

## Description

Internet retail, also known as e-commerce, is the largest sector of the electronics industry. E-commerce platforms like Shopify and WooCommerce provide a suite of services to businesses of all sizes. This E-commerce Back End is a REST API for an internal retail website. Each data group has API routes that point to each of the standard CRUD operations. The routes can be used to

    * Create products, categories and tags
    * View products, categories and tags
    * Update products, categories and tags
    * Delete any of these items from the database

Languages/Dependencies Used:

    * JavaScript
    * Node.js
    * Express.js
    * MySQL2
    * Sequelize

## Installation

- MySql server and Node.js are required on your machine.
- Clone this repo to your machine.
- Create a .env file in the root directory with the following information so you can connect to the database:<br>
  DB_NAME='ecommerce_db'<br>
  DB_USER='root'<br>
  DB_PW='your mysql password'
- run "npm install express sequelize mysql2 dotenv" from your command line

# Usage

- Log in to MySql CLI and run "source db/scehma.sql" to create the e-commerce database
- Exit out of MySql shell and run "npm run seed" from the root command line of the project to populate your database
- Enter "node server" on the command line to get the server up and running. Use your desired method (Insomnia, Postman) to make requests to the database.

# Demo

[Ecommerce.webm](https://user-images.githubusercontent.com/105396175/186544950-ad4243c6-330c-4f93-b126-c5e42152bb12.webm)

# Collaboration

Had a little help from TA's and AskBCS bot.

## License

Licensed under the <a href='https://opensource.org/licenses/ISC'>ISC</a> license.

## Questions

- Github username: <a href='https://github.com/allibrodine'>allibrodine</a>
- E-mail address: allibrodine81@gmail.com </br>
  Please feel free to e-mail me with any questions.
