# ecom-backend

## Description
The back end for an e-commerce website. This app uses Express.js, MySQL, and Sequelize to allow users to connect to the database. Supports the POST, PUT and DELETE commands.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Questions](#questions)

## Installation
The database must be created and seeded before using the application. From the command line, connect to the mysql database and run `mysql db/schema.sql`.

The database can then be seeded by running `npm run seed`, and the application is invoked with `npm start`.

Video showing the installation: https://drive.google.com/file/d/1JB4aXIwo9aLoq3mIwPwBzaCwHLCmkABH/view?usp=sharing


## Usage
At localhost:3001/api, navigate to either the /categories, /products or /tags routes to access and interact with the corresponding data.

Video showing the usage: https://drive.google.com/file/d/1nqSZ1J2dxell1bA1O6tMmefwmatIsmHn/view?usp=sharing


## License

This work is available under the [MIT License](https://opensource.org/licenses/MIT).