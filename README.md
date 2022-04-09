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

### Associations

*You'll need to execute association methods on your Sequelize models to create the following relationships between them:*

- Product belongs to Category, as a category can have multiple products but a product can only belong to one category.

- Category has many Product models.

- Product belongs to many Tag models. Using the ProductTag through model, allow products to have multiple tags and tags to have many products.

- Tag belongs to many Product models.

### Instructions on how to run the app

- Add a .env file to the root of the app with the following details

```text
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW='xxx'
```
## Demo
Please click on the following link to see the Demo video for this project:
[Link to Demo](https://watch.screencastify.com/v/UQaa3skgRPciFcQQwDpG)  

## Usage
Please first install node.js and then run the following commands into your terminal: 

git clone <from-repository-on-github>
npm install
npm start
  
Before running "npm start" command in your terminal, please make sure to update "connection.js" file with your mysql "username" and "password".

