# test-automation-assignment

## How to setup

* Install node.js v8.11.4

  * It is recommended to install node.js using **nvm** (https://github.com/creationix/nvm)

* clone this repository and run

  ```bash
  npm install
  ```

* Run the Mock API server. The bundled mock server should be available in hhttp://localhost:3000

  ```bash
  npm start
  ```

## Instructions

Write an Test Automation script that will automate the testing of the Mock RESTFul API. There's two endpoints in total:

* **Authors** - http://localhost:3000/authors
* **Books** - http://localhost:3000/books

Your test automation script should test the following HTTP methods:

* **GET** - for querying data
* **POST** - for creating new resources
* **PUT** - for updating existing resources
* **DELETE** - for deleting resources

For guidance, you may download **postman** (https://www.getpostman.com) and import the bundled collection **mock.postman_collection.json** included here. You can use it to explore the API yourself.

You may also read the mock server (json-server) docs here: https://github.com/typicode/json-server

## Requirements

* Using any programming language create a test automation script that will verify all the API endpoints and methods.
* You may use a test automation framework as needed. Some options are:
  * https://mochajs.org
  * http://robotframework.org
* As a bonus: your test automation script should also confirm the values being stored in the database are correct when it is interacting with the API. The mock server's database is based on **lowdb** https://github.com/typicode/lowdb. Your automation script may read the **db.json** file to confirm the database activities.
* Submit your automation script either via email or send us your github link.