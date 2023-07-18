[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow.svg)](https://www.ecma-international.org/ecma-262/)
[![Node.js Badge](https://img.shields.io/badge/Node.js-393?logo=nodedotjs&logoColor=fff&style=flat)](https://nodejs.org/en)
[![MySQL Badge](https://img.shields.io/badge/MySQL-4479A1?logo=mysql&logoColor=fff&style=flat)](https://www.npmjs.com/package/mysql2)
[![Sequelize Badge](https://img.shields.io/badge/Sequelize-52B0E7?logo=sequelize&logoColor=fff&style=flat)](https://sequelize.org/docs/v6/)
[![.ENV Badge](https://img.shields.io/badge/.ENV-ECD53F?logo=dotenv&logoColor=000&style=flat)](https://www.npmjs.com/package/dotenv)
[![Insomnia Badge](https://img.shields.io/badge/Insomnia-4000BF?logo=insomnia&logoColor=fff&style=flat)](https://insomnia.rest/)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
[![GitHub](https://img.shields.io/badge/GitHub-SwathiVinod19-black.svg?logo=github)](https://github.com/Swathivinod19)


# e-commerce
Back end code for an e-commerce website using Express.js API , Sequelize and MySQL database.

## Description 
Starter code is provided. I used express js, sequelize, dotenv to interact with the MySQL database that was provided.
The code syncs sequelize models to MySQL database. There are three main end points to this application. They are : 1. Categories 2. Products 3. Tags

**In Categories** :
GET all categories , GET single category by ID, POST (Create) a new category, PUT (update) an existing category by ID, and DELETE an existing category by ID.

  
**In Products** : 
GET all products , GET single product by ID, POST (Create) a new product, PUT (update) an existing product by ID, and DELETE an existing product by ID.

  
**In Tags** : 
GET all tags , GET single tag by ID, POST (Create) a new tag, PUT (update) an existing tag by ID, and DELETE an existing tag by ID.


## Table of Contents

* [Installation](#installation)
* [Usage](#usage)
* [Walkthrough Video](#Walkthrough-video)
* [Screenshots](#Screenshots)
* [License](#license)
* [Contributions](#contributions)
* [Questions](#questions)

## Installation
* Check if you have Node.js installed in your computer by typing `node -v` in your command line.
* If node is not installed, visit the [Node.js](https://nodejs.org/en) website to install. 
* Clone this project repository to your computer. 
* Use the command `npm i` or `npm install` to install all dependencies. 
* Create a file in the root directory titled `.env` and include database name and personal MySQL login information:
```
DB_NAME='YOUR DATABASE NAME'
DB_USER='YOUR USERNAME'
DB_PW='YOUR PASSWORD'
```
* Open MySQL with command `mysql -u root -p` and enter your personal MySQL password. 
* Create databse with command `source schema.sql`. Log out of MySQL with command `\q`.
* Seed database with command `npm run seed`.
* Start the server with either `npm start` or `node server.js`

## Usage
* Start server with command `npm start`or `node server.js`
* Make POST and PUT requests following the JSON formats. 
* Access API routes with Insomnia/Thunder Client using the following endpoints:

**CATEGORY/PRODUCTS/TAGS : GET(ALL), POST(CREATE)**
```
http://localhost:3001/api/categories/
http://localhost:3001/api/products/
http://localhost:3001/api/tags/ 
```
**CATEGORY/PRODUCTS/TAGS : GET(BY ID), PUT(UPDATE), DELETE**
```
http://localhost:3001/api/categories/id
http://localhost:3001/api/tags/id
http://localhost:3001/api/products/id
```


## Walkthrough Video
[Video link](https://drive.google.com/file/d/1GWgAFAmZ7Lfuy-0HEFhAnKABv0iOiROq/view)


## Screenshots

![e-commerce-GET-Categories](https://github.com/SwathiVinod19/e-commerce/assets/129353324/1ae8f49c-9741-40a2-bf5c-f227a40dda50)
GET Categories

![e-commerce-PUT-tags](https://github.com/SwathiVinod19/e-commerce/assets/129353324/7cc5eff5-f695-4ba6-bba8-2dc93f79aaa4)
PUT Tags

![e-commerce-POST-Categories](https://github.com/SwathiVinod19/e-commerce/assets/129353324/96bf26de-8dd9-4657-b6e1-52723b8a1478)
POST Categories

![e-commerce-DELETE-Products](https://github.com/SwathiVinod19/e-commerce/assets/129353324/2e7aaef6-44a1-4903-a93d-21de8f48499a)
DELETE Products



## License

[MIT License](https://opensource.org/licenses/MIT)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Contributions
I am open to ideas and contributions

## Questions

Contact : [SwathiVinod19](https://github.com/SwathiVinod19)



