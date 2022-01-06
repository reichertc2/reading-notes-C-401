# Code 401 - Advanced Software Development - Python

## Class 27 - Django Models

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### Using Models ([Article](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Models)

Models are Django's method of managing data. Or more accurately data libraries. The libraries are wired to creat relationships between information sets in Django.

In the world of models with the primer for a new model, the model has to be defined. To bring in the models from django enter the following import ```from django.db import models```. As with a lot of other items, models are classes.

Inside the models there are fields, or columns of data tables. There are a multitude of common filed arguments. One such is ```CharField``` which is used for strings short to moderate in length and must have aspecified ```max_length```.

As with data sets, it can be searched, edited. There is a great deal more on the subject, reference the above article.

### Django Admin ([Article](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Admin_site))

The admin side of django is a GUI? That was unexpected. A change from the past data management system. As for me, I tend to learn GUIs best by playing with them and getting them to work.

Another topic dicussed was the creation of a super user. It is a simple line of code in the CLI ```python manage.py createsuperuser```. Once it is created it can log into the admin side and modify as necessary. The question is now can you create users with lesser rights.

I look forward to messing around in the GUI and break things to learn how to fix them.

### Additional Resources

Beginner’s Guide to Django - Part 1 ([Article](https://simpleisbetterthancomplex.com/series/2017/09/04/a-complete-beginners-guide-to-django-part-1.html))

### Bookmark/Skim

Beginner’s Guide to Django - Part 2 ([Article](https://simpleisbetterthancomplex.com/series/2017/09/11/a-complete-beginners-guide-to-django-part-2.html))

### Things I want to know more about

* 

Go [Home](index.md)