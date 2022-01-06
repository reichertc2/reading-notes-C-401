# Code 401 - Advanced Software Development - Python

## Class 28 - Django CRUD and Forms

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### Django Forms ([Article](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Forms))

The dreaded form. It is often a source of stress to get it to communicate correctly with the backend. I find myself referring to older successful code for new code implementations. It's no too intutive for me, yet.  Django on the other hand sounds as though it is a more simple process, just need to know the django-eese.

Where do I pull them into a file? ```from django import forms```.

A baseline for Forms is a ModelForm. It is a class within Django. It is very flexible to customize your form to your needs.  The negative side is it requires a map its fields to a single models fields, i.e. fields, labels, help-text etc.  

Additionally adding validation is a relatively painless process. You define the function ```clean_field_name()``` and ```ValidationError```, these are located in the base ModelForm. 

I look forward to playing  with this functionality. It seems a bit less intimidating than React's way of doing things.

### Bookmark/Skim

Django Templates ([Article](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Home_page))

Django Views ([Article](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Django/Generic_views))

### Things I want to know more about

* 

Go [Home](index.md)