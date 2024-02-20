# Permissions & Postgresql

## Notes

- Django REST Framework supports permissions, authentication, and throttling to control access to an API
- Permissions can be set by view or model

## Reading Questions

1. **What are the key components and purpose of Django Rest Framework (DRF) permissions, and how do they help in securing an API?**

    Permissions is one of the methods that can be used to control if a request to should be allowed. Permissions to can be used to grant different access levels, such as read-only, to the views and models in an API.

1. **In SQL, what is the purpose of the SELECT statement, and how would you use it to retrieve all columns from a table called ‘employees’?**

    The `SELECT` statement is used to query a database and retrieve the data requested by the statement.

    ```sql
    SELECT *
    FROM employees;
    ```

    This would select all columns from an "employees" table

1. **Can you explain the role of DRF Generic Views and provide examples of their usage in building a RESTful API?**

    DRF generic views use Django class-based views to provide quick setup of CRUD operations with a database. For example, the `CreateAPIView` can be used for an endpoint to create resources via an HTTP POST method.

## Things I want to know more about

- Access control concepts for APIs and how to implements them across this and different API frameworks.

## References

- [Django REST Framework Docs: Permissions](https://www.django-rest-framework.org/api-guide/permissions/)
- [Django REST Framework Docs: Generic views](https://www.django-rest-framework.org/api-guide/generic-views/)
- [Classy Django REST Framework](https://www.cdrf.co/)
- [SQLBolt](https://sqlbolt.com/)
