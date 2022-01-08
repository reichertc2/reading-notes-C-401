# Code 401 - Advanced Software Development - Python

## Class 29 - Django Custom User

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### Django Custom User Model ([Article](https://learndjango.com/tutorials/django-custom-user-model))

Creating an user system is important, especially if you want users to return. Pretty much every site has them. Django has them as a default, but it is recommended to create a Custom User Model.  

There are two possible choices: AbstractUser and AbstractBaseUser. Of these two the AbstractUser is the simplified one.  From what I read, The base user version requires a lot more setup.

The author recommends creating a project with user access in mind. To create the user model prior to making any migrations, will alleiviate al ot of headaches. Here is an example user model: 
```
from django import forms
from django.contrib.auth.forms import UserCreationForm, UserChangeForm
from .models import CustomUser

class CustomUserCreationForm(UserCreationForm):

    class Meta:
        model = CustomUser
        fields = ('username', 'email')

class CustomUserChangeForm(UserChangeForm):

    class Meta:
        model = CustomUser
        fields = ('username', 'email')
```

### DjangoX ([Article](https://github.com/wsvincent/djangox))

It looks pretty cool as far as the complexity, I need to dive more into this, eventually.

### Additional Resources

Creating a Custom User Model ([Video](https://www.youtube.com/watch?v=eCeRC7E8Z7Y&t=59s))
```or```
Abstract User, User Profile and Signals in Django ([Video](https://www.youtube.com/watch?v=EudKs1HPUfE))

The process of creating a AbstractBaseUser is quite intensive. I look forward to creating one. It has a lot of steps and tie ins, the docs look vague in comparison. 

### Bookmark/Skim

Substituting a custom User model ([Article](https://docs.djangoproject.com/en/3.0/topics/auth/customizing/#auth-custom-user))

### Things I want to know more about

* 

Go [Home](index.md)