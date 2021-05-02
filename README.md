### ecommerce-database

 A mysql database and application backend for an e-commerce site. Built using MySQL2, Express, Sequelize and dotenv.

### Below is the gif showing the functionality of the application:

### DB Setup and Start

GET All
![image](https://user-images.githubusercontent.com/76706062/116801559-1d3b9000-aad9-11eb-87ee-69c59f758268.png)
GET All by ID
![image](https://user-images.githubusercontent.com/76706062/116801553-1745af00-aad9-11eb-9b94-da122ea2b9ce.png)

POST PUT DELETE Products and Tags
![image](https://user-images.githubusercontent.com/76706062/116801545-06953900-aad9-11eb-8046-b5d69c846347.png)

POST PUT DELETE Categories
![image](https://user-images.githubusercontent.com/76706062/116801548-0e54dd80-aad9-11eb-8ae7-e41485d471a9.png)

The full movie file showing functionality of the application can be found in the animations directory

### User Story
AS A manager at an internet retail company
I WANT a back end for my e-commerce website that uses the latest technologies
SO THAT my company can compete with other e-commerce companies
Acceptance Criteria
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

### Table of Contents
Description
User Story
Acceptance Criteria
Table of Contents
Installation
Usage
Testing
Contributing
Questions

### Installation
💾

npm init

npm install mysql2

npm install sequelize

npm install dotenv

### Usage

## Run the following command at the root of your project and answer the prompted questions:

mysql -u root -p

Enter PW when promted

source db/schema.sql

quit

npm run seed

npm start


