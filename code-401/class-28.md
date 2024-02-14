# Django CRUD and Forms

## Reading Questions

1. **How do Django Forms facilitate user input handling, and what are some key components of creating a form using the Django framework?**

    The Django framework includes user input functionality that can be used to create forms, validate form data, perform actions with form data, and interact with the user of the form.

    - *Model*
      - `Form` a class used to declare a form and specify its fields. Can be mapped to a model for data persistence.
      - `ModelForm` a class which creates a form using the fields from an existing model.
    - *View*
      - Generic views for CRUD operations: `CreateView`, `UpdateView`, `DeleteView`, also `FormView`

1. **Explain the purpose of Django Templates in web development and describe how template inheritance can be utilized to improve code reusability and maintainability.**

    A template is an HTML page used to define the structure and layout of a page. It used Django template tags to create placeholders for data that are added in from views. Templates can be used to create *template* pages that are used to create consistent designs and reduce duplication of code.

1. **Describe the function of Django Views in handling HTTP requests, and outline the differences between function-based views and class-based views.**

    Views are used to retrieve and render data in template pages.

    - Function-based: Custom defined functionality which renders the template
    - Class-based: Extends an existing generic view class to interact with the model and provide data to the template

## Things I want to know more about

- How views interact with the model and template

## References

- [MDN: Django Forms](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms)
- [MDN: Django Templates](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page)
- [MDN: Django Views](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views)
