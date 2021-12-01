# Code 401 - Advanced Software Development - Python

## Class 03 - FileIO & Exceptions

Block intro

> For to be free is not merely to cast off one’s chains, but to live in a way that respects and enhances the freedom of others - Nelson Mandela

### Read & Write Files in Python ([Article](https://realpython.com/read-write-files-python/))

Reading and writing files couldn't be more simple. Just a little bit of expected_magic and boom. All done.

Not. It is quite amazing what we take advantage of when we are just an end user of any application. The parts of the fileL header, data, and EOF. Never knew they existed. The most interesting part was the complex method of ```open()``` and ```close()``` are replaced with ```with()```, to mitigate system resources drain. 

The read and write on files are useful too, I assume. I guess we'll have to wait and see.

### Exceptions in Python ([Article](https://realpython.com/python-exceptions/))

I thought ```try {} catch {}``` would be missed. I thought wrong. Not only wrong, but there are two extra options ```else:``` and ```finally:```.

The other change is the ```catch {}``` is now ```except:```. Thus leading to my next pearl of knowledge. Exceptions are the new errors, excluding the syntax errors. Exceptions are only run when the syntactically correct code encounters an error.

```
def blank_function():
    try: # primary code to run, assuming no exceptions are encountered
    except: # code that runs if an exception is hit
    else: # code that runs if no exceptions are encountered
    finally: # code that runs no matter what
```

### Additional Resources

Read & Write Files in Python - Companion Video ([Video](https://realpython.com/courses/reading-and-writing-files-python/))

### Bookmark/Skim

Reading and Writing Files in Python Quiz ([Article](https://realpython.com/quizzes/read-write-files-python/))

### Things I want to know more about

* 

Go [Home](index.md)