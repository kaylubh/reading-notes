# Authentication & Production Server

## Reading Questions

1. **What is the primary purpose of JSON Web Tokens (JWTs) and how do they work in terms of encoding and decoding data?**

    JWTs are primarily used to provide user authorization and data integrity for web requests. The work by encoding and signing a web request using its header and payload to create a signature with verifies the authenticity of the request when it is received.

1. **How does JWT Authentication integrate with Django REST Framework to secure API endpoints, and what are the key components involved in this process?**

    JWT integrates with Django REST Framework (DRF) to create access and refresh tokens used to authenticate requests handled by DRF.

    Set up:

    ```bash
    pip install djangorestframework_simplejwt
    ```

    ```python
    # settings.py

    REST_FRAMEWORK = {
      'DEFAULT_AUTHENTICATION_CLASSES': [
        'rest_framework_simplejwt.authentication.JWTAuthentication',
      ],
    }

    ##########

    # urls.py

    from django.urls import path
    from rest_framework_simplejwt import views as jwt_views

    urlpatterns = [
      # access tokens paths
      path('api/token/', jwt_views.TokenObtainPairView.as_view(), name='token_obtain_pair'),
      path('api/token/refresh/', jwt_views.TokenRefreshView.as_view(), name='token_refresh'),
    ]
    ```

1. **Why is Django’s built-in runserver not suitable for production environments, and what are some alternative server options that should be considered for deploying a Django application?**

    The built-in development server `runserver` is not suitable for production because it is not designed for performance and most importantly does not address security of the server. When deploying a production environment you will need a web server such as Nginx and an application server such as Gunicorn or WhiteNoise. If deploying on a cloud service, they provide the web server and the only thing you need to add is an application server.

## Things I want to know more about

- How the "SECRET" for the JWTs is determined or shared

## References

- [JWT: Introduction to JSON Web Tokens](https://jwt.io/introduction/)
- [Simple is Better Than Complex: How to Use JWT Authentication with Django REST Framework](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html)
- [vsupalov: Django Runserver Is Not Your Production Server](https://vsupalov.com/django-runserver-in-production/)
