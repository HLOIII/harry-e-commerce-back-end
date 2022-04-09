# harry-e-commerce-back-end

### Description

*Build the back end for an e-commerce site. Take a working Express.js API and configure it to use Sequelize to interact with a MySQL database.*

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
WHEN I open API GET routes in Insomnia for categories, products, or tags
THEN the data for each of these routes is displayed in a formatted JSON
WHEN I test API POST, PUT, and DELETE routes in Insomnia
THEN I am able to successfully create, update, and delete data in my database

# Tests
Run the following command "node server.js" multiple times in your terminal. Use "Insomnia Core" or "Postman" to test the routes for Category, product and Tag models.

## Demo
Please click on the following link to see the Demo video for this project:
[Link to Demo](https://watch.screencastify.com/v/UQaa3skgRPciFcQQwDpG)  

## Usage
Please first install node.js and then run the following commands into your terminal: 

git clone <from-repository-on-github>
npm install
npm start
  
Before running "npm start" command in your terminal, please make sure to update "connection.js" file with your mysql "username" and "password".

