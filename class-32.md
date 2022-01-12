# Code 401 - Advanced Software Development - Python

## Class 32 - Permissions & Postgresql

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### DRF Permissions ([Article](https://www.django-rest-framework.org/api-guide/permissions/))

Permissions are vital to the control and flow of information. ```djangorestframework``` brings a lot to the table. Permissions are determined by checking a permissions list. if the check is accepted the permission is granted. If it fails either a 403 or 401 response is returned.

An example of unrestricted access if it is not specified is unrestricted:
```
REST_FRAMEWORK = {
    'DEFAULT_PERMISSION_CLASSES': [
        ''rest_framework.permissions.AllowAny',
    ]
}
```

Here is a list of some API References:
- AllowAny
- IsAuthenticated
- IsAdminUser
- IsAuthenticatedOrReadOnly


### Bookmark/Skim

Classy Django REST ([Article](https://www.cdrf.co/))

DRF Generic Views ([Article](https://www.django-rest-framework.org/api-guide/generic-views/))

### Things I want to know more about

* 

Go [Home](index.md)