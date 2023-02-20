## 1. Getting started with Django

        in this part we will discuss the following points

* Object-relational mapper
* URLs and views
* Templates
* Forms
* Authentication
* Admin
* Internationalization
* Security

<br/>

                           The beginning of Part One

### 1.1: Object-relational mapper:

Deﬁne your data models entirely in Python. 

Model is : A model is the single, definitive source of information about your data. It contains the essential fields and behaviors of the data you’re storing. Generally, each model maps to a single database table.

The basics:

* Each model is a Python class that subclasses django.db.models. Model.
* Each attribute of the model represents a database field.
* With all of this, Django gives you an automatically-generated database-access API; 

### 1.2: URLs and views

To design URLs for an application, you create a Python module called a URLconf. Like a table of contents for your app, it contains a simple mapping between URL patterns and your views.

* How Django processes a request?
When a user requests a page from your Django-powered site, this is the algorithm the system follows to determine which Python code to execute:

1. Django determines the root URLconf module to use. Ordinarily, this is the value of the ROOT_URLCONF setting, but if the incoming HttpRequest object has a urlconf attribute (set by middleware), its value will be used in place of the ROOT_URLCONF setting.
2. Django loads that Python module and looks for the variable urlpatterns. This should be a sequence of django.urls.path() and/or django.urls.re_path() instances.
3. Django runs through each URL pattern, in order, and stops at the first one that matches the requested URL, matching against path_info.
4. Once one of the URL patterns matches, Django imports and calls the given view, which is a Python function (or a class-based view). The view gets passed the following arguments:
    - An instance of HttpRequest.
    - If the matched URL pattern contained no named groups, then the matches from the regular expression are provided as positional arguments.
    - The keyword arguments are made up of any named parts matched by the path expression that are provided, overridden by any arguments specified in the optional kwargs argument to django.urls.path() or django.urls.re_path().
5. If no URL pattern matches, or if an exception is raised during any point in this process, Django invokes an appropriate error-handling view. See Error handling below.

### 1.3: Templates

A Django project can be configured with one or several template engines (or even zero if you don’t use templates). 

### 1.4: Forms

In the context of a Web application, ‘form’ might refer to that HTML <form>, or to the Django Form that produces it, or to the structured data returned when it is submitted, or to the end-to-end working collection of these parts.

### 1.5: Authentication

The Django authentication system handles both authentication and authorization. Briefly, authentication verifies a user is who they claim to be, and authorization determines what an authenticated user is allowed to do. 

### 1.6: Admin

One of the most powerful parts of Django is the automatic admin interface. It reads metadata from your models to provide a quick, model-centric interface where trusted users can manage content on your site. The admin’s recommended use is limited to an organization’s internal management tool. It’s not intended for building your entire front end around.

### 1.7: Internationalization

The goal of internationalization and localization is to allow a single Web application to offer its content in languages and formats tailored to the audience.

### 1.8: Security

Django provides multiple protections against:

* Clickjacking
* Cross-site scripting
* Cross Site Request Forgery (CSRF)
* SQL injection
* Remote code execution

<br/>

    
                               The End of Part One

## 2. How Django Works Behind the Scenes

        in this part we will discuss the following points

* How Django Works Behind the Scenes ?

<br/>

                           The beginning of Part Tow

### 2.1: How Django Works Behind the Scenes?

Django’s code is open source and available to all. Django’s organization is managed by a non-profit, the DSF, with a miniscule budget. And Django code is lead by a core team of volunteers, two paid Django Fellows, and a larger group of contributors.

<br/>

    
                               The End of Part Tow

# [BACK TO HOME](https://jehadabuawwad.github.io/reading-notes)

`
