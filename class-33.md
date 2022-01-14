# Code 401 - Advanced Software Development - Python

## Class 33 - Authentication & Production Server

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### JSON Web Tokens ([Article](https://canvas.instructure.com/courses/3800230/discussion_topics/13136462))

JWT is a compact and self contained way for securley transmitting information across the web. It is light weight compared to the XML options mostly because JWT can easily passed into HTML and HTTP environments.

There are three main parts to the structure of the JWT. These are teh Header, Payload, and Signature. 

The header structure:
- the type of token
- the signing algorithm

The Payload structure:
- Claims
    - registered
    - public
    - private

The Signature is created by the encoding of the header and payload.

### DRF JWT Authentication ([Article](https://simpleisbetterthancomplex.com/tutorial/2018/12/19/how-to-use-jwt-authentication-with-django-rest-framework.html))

The package used for this tutorial is ```djangorestframework_simplejwt```.

Below is some code to setup the JWT in the context of the above package.
I the project level:
- setting.py ->
```
REST_FRAMEWORK = {
    'DEFAULT_AUTHENTICATION_CLASSES': [
        'rest_framework_simplejwt.authentication.JWTAuthentication',
    ],
}
```

- urls.py ->
```
from django.urls import path
from rest_framework_simplejwt import views as jwt_views

urlpatterns = [
    # Your URLs...
    path('api/token/', jwt_views.TokenObtainPairView.as_view(), name='token_obtain_pair'),
    path('api/token/refresh/', jwt_views.TokenRefreshView.as_view(), name='token_refresh'),
]
```

### Django Runserver Is Not Your Production Server ([Article](https://vsupalov.com/django-runserver-in-production/))

Running your local server versus running on a production, I always thought they were the same. Guess not, makes sense to get it to the production as fast as possible. To modify you Django project in the ```uwsgi,py``` file. Which contains a function that calls the HTTP response and returns the web server info to the HTTP.

### Additional Resources

JWT with DRF ([Video](https://www.youtube.com/watch?v=Fhcn2qx-4VQ))

### Bookmark/Skim

Gunicorn ([Article](https://gunicorn.org/))

Django Migrations Primer ([Article](https://realpython.com/django-migrations-a-primer/))

### Things I want to know more about

* 

Go [Home](index.md)