# Django REST Framework & Docker

## Notes

- Docker is made up of linux containers
- Django REST is an app installed in Django

## Reading Questions

1. **What are the key components of a Docker container, and how do they help streamline the development and deployment of applications?**

    Docker containers are linux containers which are virtual systems for developing and deploying applications on. By using the same the container for development it creates a consistent and shared environment for developers to work on on a project in and reduces dependency/compatibility issues for deployments.

    - Image: a snapshot of a project
    - Container: a running instance of an image

1. **Describe the primary steps involved in building a library website using Django, including essential components like models, views, and templates.**

    - Install Django
    - Create a Django project and apps
    - Create model to store books
    - Register the book model
    - Create a super user
    - Add some books via the admin panel using the super user
    - Create views for the books to enable CRUD with the books model
    - Create URLs for the views
    - Create templates for the views
    - Writes tests to verify functionality of the model and templates

1. **Can you explain the primary differences between Django and Django REST framework?**

    Django is a framework to manage and serve webpages to a client. Django REST extends the functionality of Django to be able to manage endpoints which serve JSON data to clients via web APIs.

## Things I want to know more about

- What are the benefits to using Docker as an individual developer?

## References

- [wsvincent.com: A Beginner's Guide to Docker](https://wsvincent.com/beginners-guide-to-docker/)
- [Django for APIs: Chapter 3: Library Website](https://djangoforapis.com/library-website-and-api/)
- [LearnDjango: Official Django REST Framework Tutorial - A Beginners Guide](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)
