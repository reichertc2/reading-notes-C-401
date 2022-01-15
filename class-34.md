# Code 401 - Advanced Software Development - Python

## Class 34 - API Deployment

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### Django Settings Best Practices ([Article](https://djangostars.com/blog/configuring-django-settings-best-practices/))

I know configuration is vital to any successful setup. It goes to show Django is not different. The idea is to get your project to be as seamless and portable as possible. If the configuration is specific to an environment, it will break in others, possibly.

One best practice is to incorporate a ```.env``` file. Which is smart, otherwise all your relevent info is out for the world to see. 

Another convention is the use of ```django-environ```.  It can be easier to use than the ```os.environ```. 

Another convention is the 12 factors created by Heroku:
- Codebase
- Dependencies
- Config
- Backing Services
- Build, Release, run
- Processes
- Port binding
- Concurrency
- Disposability
- Dev/prod parity
- Logs
- Admin processes

### SSH Tutorial ([Article](https://www.hostinger.com/tutorials/ssh-tutorial-how-does-ssh-work))

SSH an process of access for two machines to work together. A secure shell (SSH). Is the current way to permit access between machines. In a nut shell it is a symmetrical encryption, which have both hidden and public keys. Only the public key is know to the public, and the secret key is known only to the machines. The encryption cannot be decrypted without the private keys.

### Bookmark/Skim

White Noise ([Article](https://whitenoise.evans.io/en/stable/))

IaaS ([Article](https://en.wikipedia.org/wiki/Infrastructure_as_a_service))

PaaS ([Article](https://en.wikipedia.org/wiki/Platform_as_a_service))

CORS ([Article](https://en.m.wikipedia.org/wiki/Cross-origin_resource_sharing))

### Things I want to know more about

* 

Go [Home](index.md)