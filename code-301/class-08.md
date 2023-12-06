# APIs

## API Design Best Practices

1. **What does REST stand for?**

    Representational State Transfer

2. **REST APIs are designed around a ____.**

    Resource

3. **What is an identifier of a resource? Give an example.**

    An identifier would be a URI which is unique to that resource.

    `https://resource-identifier/49nf7`

4. **What are the most common HTTP verbs?**

    - `GET`
    - `POST`
    - `PUT`
    - `PATCH`
    - `DELETE`

5. **What should the URIs be based on?**

    URIs should be based on nouns, representing the resource, and not verbs, representing actions to take with or on the resource.

6. **Give an example of a good URI.**

    `https://awesome-website/form` GOOD

    `https://awesome-website/submit-form` BAD

7. **What does it mean to have a ‘chatty’ web API? Is this a good or a bad thing?**

    It means having an API that requires a large number of requests which each return a small resource and might require multiple requests in order to get the resource(s) required. While it can reduce the size of resources sent to a client, it may increase the number of requests needed to get a resource which could slow things down or use even more bandwidth. Finding the right balance is dependent on the application and data.

8. **What status code does a successful `GET` request return?**

    200 (Ok)

9. **What status code does an unsuccessful `GET` request return?**

    400

10. **What status code does a successful `POST` request return?**

    201 (Created)

11. **What status code does a successful `DELETE` request return?**

    204 (No Content)

## Things I want to know more about

- Best/common practices for sending which status codes on particular requests

## References

- [Microsoft Azure Docs: RESTful web API design](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
