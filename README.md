# Baby Got BackEnd

![License: MIT](https://img.shields.io/badge/license-MIT-orange)

## Description

This application is used to build an back end for e-commerce for a database which includes categories, products, and tags

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [License](#license)


## Installation

Please have node.js installed onto your machine
- Install node version v16.18.0 by following instructions here: https://coding-boot-camp.github.io/full-stack/nodejs/how-to-install-nodejs



## Usage
- Pull up your CLI

- Verify correct node version by typing in "node -v"

- Run "npm i"

- Log into your mysql, and source the schema file in /db. Verify correct database by typing 'USE ecommerce_db', and type 'quit' to exit out of mysql

- Click on the env.EXAMPLE file, and add your mysql password to "DB_PASSWORD". Be sure to rename the file to ".env" by deleting "example" from the file name for the application to operate properly

- Run "npm run seed" to seed the database

- Run "npm start" in the CLI to start the application

- Open the Insomnia app, and using "http://localhost:3001/api/" you will be able to use different routes

<a href = 'https://drive.google.com/file/d/1Hr22JwAPlDSFbkOCSqCT-KBFc32aRSkg/view'> Demo Video </a>

![](./assets/Screenshot%202023-04-02%20214924.png)

## License

This project is licensed under the MIT license
https://opensource.org/license/mit/



