# Code 401 - Advanced Software Development - Python

## Class 08 - Game of Greed 3

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->

### List Comprehensions ([Article](https://www.pythonforbeginners.com/basics/list-comprehensions-in-python))

List comprehensions are the one liners for the list (array) in python. A simple syntax from the article is ```digits = [x for x in range(10)]```. Another portion of list comprehension can be used ina for loop. List comprehensions can be used on any type of list be it integers, strings, etc.

A helpful use for list comprehension is parsing a file. An example of this is from the article:

```
# open the file in read-only mode
file = open("dreams.txt", 'r')
poem = [ line for line in file ]

for line in poem:
    print(line)
```

Adding arguments for list comprehension still not too sure on how to do this, I will need to practice this.

### Bookmark/Skim

Primer on Decorators ([Article](https://realpython.com/primer-on-python-decorators/))

### Additional Resources

Debugging with PySnooper ([Audio](https://www.pythonpodcast.com/pysnooper-python-debugging-episode-241/))

### Things I want to know more about

* 

Go [Home](index.md)