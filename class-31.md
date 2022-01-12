# Code 401 - Advanced Software Development - Python

## Class #31 - Django REST Framework & Docker

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### Beginner’s Guide to Docker ([Article](https://wsvincent.com/beginners-guide-to-docker/))

I've heard about the Docker Container before. It is nice to have a breakout from just a high level. Essentially a docker is a self sustaining environment. It has a base system like linux to run on, which is installed on the hardware. The docker then runs in sequence to set up the application environment. It is not dedicated to a single machine. A hardware machine often runs multiple docker containers.

In short, docker containers are light weight and fast compared to virtual machines. The major downside is due to its simple nature, it doesn't scale very well. An example code base from the article for a simple container is:

```
# Dockerfile

# Python version
FROM python:3.7-alpine

# Set environment variables
ENV PYTHONDONTWRITEBYTECODE 1
ENV PYTHONUNBUFFERED 1

# Set work directory
WORKDIR /code

# Install dependencies
COPY Pipfile Pipfile.lock /code/
RUN pip install pipenv && pipenv install --system

# Copy project
COPY . /code/
```

### Django for APIs - Library Website ([Article](https://djangoforapis.com/library-website-and-api/))

APIs are essential for importing existing information. I guessed there would be a convention on how to execute. It is similar to organizing your files for others to use. Keeping it simple. Creating a new app for apis and writing the apis in that app. 

### Bookmark/Skim

Beginner’s Guide to Django REST Framework ([Article](https://learndjango.com/tutorials/official-django-rest-framework-tutorial-beginners)) 

### Things I want to know more about

* 

Go [Home](index.md)