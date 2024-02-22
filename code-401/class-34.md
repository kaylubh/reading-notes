# API Deployment

## Reading Questions

1. **What are the key principles to follow when organizing and configuring Django settings for a project, according to the “Django Settings Best Practices” reading?**

    When configuring the Django settings, there are likely to be different settings needed in different environments such as development and production environments. The easiest way to handle this is to create an environment file and store the values of changing settings in this environment file. This allows you have an environment on local development as well as deployed production such as Docker containers.

1. **How does the White Noise library contribute to the efficient serving of static files in a Django application, and what are the steps to integrate it into a project?**

    The WhiteNoise library allows you to organize your static files in a Django application so that they can be used in a production server.

    Set Up:

    ```bash
    pip install whitenoise
    ```

    ```python
    # settings.py

    ...

    MIDDLEWARE = [
      # ...
      "django.middleware.security.SecurityMiddleware",
      "whitenoise.middleware.WhiteNoiseMiddleware",
      # ...
    ]

    ...

    STATIC_ROOT = BASE_DIR / "staticfiles"
    ```

1. **What is the purpose of Cross-Origin Resource Sharing (CORS) in web applications, and how can it be implemented and configured in a Django project to control access to resources?**

    CORS is used in web applications to allow HTTP requests to be sent across multiple domains such as a separate domain that handles the API for a web application.

## Things I want to know more about

- Are there additionally security considerations when enabling CORS, how do you restrict it to only approved domains

## References

- [Django Stars: Configuring Django Settings: Best Practices](https://djangostars.com/blog/configuring-django-settings-best-practices/)
- [WhiteNoise Docs](https://whitenoise.readthedocs.io/en/stable/)
- [Wikipedia: Cross-origin resource sharing](https://en.m.wikipedia.org/wiki/Cross-origin_resource_sharing)
