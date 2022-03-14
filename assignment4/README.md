# Company Inventory Page

This is the Fourth Assignment of CS648 course. It is a SPA created using React, served using Express, Graphql for API integration and MongoDB as the database. A simple inventory page where one can add some product and view all the products added.\
The initial setup comes from Assignment 3 repo and this repo is a clone of that with new changes for Assignment 4.

## Initial Step

Go to Api folder and run `npm run install` to install all the dependencies.\
Go to Ui folder and run `npm run install` to install all the dependencies.

## Development server

Go to Api folder and run `npm run start` to bring up the Api server.\
Go to Ui folder and run `npm run start` to bring up the UI.\
Now Navigate to `http://localhost:8000/` to interact with the application.


## MongoDB reset

From Api folder, you can run `mongo "mongodb+srv://Cluster0.yxyis.mongodb.net/inventoryTracker" --username mansi261 scripts/init.mongo.js` and enter password as `Abc123` to reset the database with two products added initially.

