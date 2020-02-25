Overview

In the previous unit, we modularized our applications following the MVC paradigm and integrated a custom ORM into the Model layer. Like all things in software development, when we find ourselves repeating a task, we look for programmatic solutions. Because the implementation of object-relational mapping is a common task in full-stack web development, third-party libraries emerged to do the heavy-lifting for us. In this unit we will integrate Sequelize, a popular Node.js ORM, into our newly modularized applications.


Key Topics


Sequelize
sequelize-cli
CRUD
Models
Validations
Associations



Comprehension Check

You will be employer-ready if you can answer the following questions:


What is a Model? 
What are two approaches to using Sequelize in a full-stack web application? 
How does one perform joins using Sequelize?



Learning Objectives

You will be employer-competitive if you are able to:


Configure a full-stack web application to use the Sequelize ORM library
Define models that POST data using validations
Define models that GET data using validations
Implement CRUD methods using Sequelize
Implement Sequelize associations to join one or more tables
Configure Heroku for deployment of an application using Sequelize

#├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars

 link to the website: 

 "https://afternoon-tor-10929.herokuapp.com/"
 *Hayder Achir*
