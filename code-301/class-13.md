# More CRUD

## CRUD Basics

1. **Which HTTP method would you use to update a record through an API?**

    If you are updating a record through an API the most appropriate HTTP method to use is `PUT`.

2. **Which REST methods require an ID parameter?**

    The methods `PUT` and `DELETE` require an ID parameter because they are being used to update or deleting an existing resource. The ID is necessary in order for the application to know which resource to update or delete.

## Building a CRUD API

1. **What’s the relationship between REST and CRUD?**

    The CRUD concept of Create, Read, Update, and Delete is implemented by using the REST HTTP methods of POST, GET, PUT, and DELETE respectively.

2. **If you had to describe the process of creating a RESTful API in 5 steps, what would they be?**

    1. Create a basic API server with Node JS and Express
    2. Set up the routes necessary to handle each part of CRUD
    3. Set up a database to store the resources
    4. Seed the API database
    5. Test the routes to make sure they create, read, update, and delete from the database

## Things I want to know more about

- What is the `PATCH` HTTP method used for?
- What is the router in Express?

## References

- [Geek Culture: CRUD Operations Explained](https://medium.com/geekculture/crud-operations-explained-2a44096e9c88)
- [Coding Garden: SPEED RUN: Build a CRUD API with Node.js + Express + MongoDB](https://www.youtube.com/watch?v=EzNcBhSv1Wo)
