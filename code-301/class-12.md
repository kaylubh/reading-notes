# CRUD

## Status Codes Based On REST Methods

1. **In your own words, describe what each group of status code represents:**

    - **100’s =** Information codes that let a client know a request has been received
    - **200’s =** Success codes that say a request was successful or received for processing
    - **300’s =** Redirection if a resource has moved
    - **400’s =** Client errors
    - **500’s =** Server errors

2. **What is a status code 202?**

    "Accepted" This code lets the client know the request was accepted but is being processed asynchronously and will finish being processed at some time in the future.

3. **What is a status code 308?**

    "Permanent Redirect" This means the URL is no longer in use to access this resource anymore and has moved to a different URL

4. **What code would you use if an update didn’t return data to a client?**

    Code 204 No Content

5. **What code would you use if a resource used to exist but no longer does?**

    Code 410 Gone

6. **What is the ‘Forbidden’ status code?**

    Code 403 Forbidden

## REST API With Node.js, Express, & MongoDB

1. **Why do we need to pull our MongoDB database string out of our server and put it into our .env?**

    You need to pull the database string out because the location of the database will vary between development and deployed environments of the application.

2. **What is middleware?**

    Middleware is code that runs when the server gets a request before it is processed by the routes.

3. **What does app.use(express.json()) do?**

    This enables the express server to accept JSON data.

4. **What does the /:id mean in a route?**

    It is a parameter that allows you access the information in the path of the URL from the client.

5. **What is the difference between PUT and PATCH?**

    PUT is used to update everything in a record while PATCH is used to make a partial change.

6. **How do you make a default value in a schema?**

    You add a default attribute to the property type definition in the schema.

7. **What does a 500 error status code mean?**

    It means there was an error on the server and the error is not the fault of the client.

8. **What is the difference between a status 200 and a status 201?**

    Status 200 means successful but 201 further clarifies that it was successful and a new resource was created.

## Things I want to know more about

- Does the client side of an application automatically take any actions based on a HTTP request code or only if a developer adds that functionality?

## References

- [Moesif Blog: Which HTTP Status Code to Use for Every CRUD App](https://www.moesif.com/blog/technical/api-design/Which-HTTP-Status-Code-To-Use-For-Every-CRUD-App/)
- [Web Dev Simplified: Build A REST API With Node.js, Express, & MongoDB - Quick](https://www.youtube.com/watch?v=fgTGADljAeg)
