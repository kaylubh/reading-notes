# Intro to Django

## Reading Questions

1. **What are the key components of the Django framework, and how do they contribute to building a web application?**

    Django is a web development framework written in Python which provides tools and libraries of common web app requirements.

    - Data model
    - API creation
    - User authentication
    - Administration interface
    - Path/URL management
    - Page templates

1. **Explain the role of Django’s MVT (Model-View-Template) architecture and how it handles a typical web request-response cycle.**

    Django uses the Model-View-Template (MVT) architecture:

    - Model: Python classes which represent database tables
    - View: Views receive user input, interact with models, and return templates to be rendered
    - Template: Templates are dynamically generated pages presented to the user

1. **What is the purpose of Tailwind CSS, and how does it differ from Bootstrap CSS?**

    Tailwind CSS provides a CSS framework that allows you to create front-end web features and components using utility classes. Tailwind differs from Bootstrap because it is considered a low-level framework that only provides the CSS utility classes to create components. This means it doesn't have full featured or style components like menus, dropdowns, navbars, etc but it conversely allows a greater degree of customization when building those components.

## Things I want to know more about

- Is adding styles or additional CSS to Tailwind components similarly difficult to styling Bootstrap components?

## References

- [Django Docs: Getting started with Django](https://www.djangoproject.com/start/)
- [Hubspot: Tailwind CSS: What It Is, Why Use It & Examples](https://blog.hubspot.com/website/what-is-tailwind-css)
