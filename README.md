# wei-e-commerce-back-end

## Description

This application is the creation of back-end for the e-commerce site. Express.js and Sequelize were used in this project to interact with the MySQL database. The application is able to GET, POST, PUT, and DELETE data from the database, which is used to display, create, update and delete the products, categories, and tags on the front-end of the application.

## Installation

Before using this application, please make sure you have these programs installed:

- Visual Studio Code
- Node.js
- MySQL database

Next, please use the following code to clone this repository and make sure the package.json file is included.

```
$ git@github.com:WeitheFang/wei-e-commerce-back-end.git
$ cd wei-e-commerce-back-end
```

You will also need to place a .env file in the root directory of the project, in order to connect to your MySQL database. Here's the format used by this application:

file: .env

```
DB_NAME='ecommerce_db'
DB_USER='root'
DB_PW=''
```

## Usage

Once the required programs are installed, please run:

```
npm i
```

Next, please create a MySQL database on your local machine using the schema.sql file located in the /db/ directory(From the MySQL CLI, source db/schema.sql)

Then run the following code in terminal to initiate the seeding process:

```
npm run seed
```

Finally, run the following command to start the server:

```
npm start
```

From there, simply run the port on Insomnia to test the GET/POST/PUT/DELETE method on the backend of the application.

Walkthrough video for the application: https://drive.google.com/file/d/1cKaxMyNZjaUhbWn3fc2-sg5bg0gZ5a7M/view?usp=sharing

## Credits

N/A

## License

No license used
