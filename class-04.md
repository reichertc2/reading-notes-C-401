# Code 401 - Advanced Software Development - Python

## Class 03 - Topic

Block intro

> An investment in knowledge pays the best interest. –  Benjamin Franklin

### Classes and Objects ([Article](https://www.learnpython.org/en/Classes_and_Objects))

Well not too much new here, from JavaScript at least. The class looks and is adjusted fairly similarly.  Below is an example on how to create a class as listed in the article:

```
class Vehicle:
    name = ""
    kind = "car"
    color = ""
    value = 100.00
    def description(self):
        desc_str = "%s is a %s %s worth $%.2f." % (self.name, self.color, self.kind, self.value)
        return desc_str
```

Another part of the class is the ```__init__```. It is used to assign values in the class. it looks like this:

```
class Vehicle:
   def __init__(self, number):
       self.number = number
```

We shall see how accurate I am in the coming days.

### Thinking Recursively ([Article](https://realpython.com/python-thinking-recursively/))

The theoretical recursive is something I comprehend. The execution is another story. I guess the Fibonacci is the premier example of the recursive. I would like to know another real world example of recursive functionality.

Fibonacci:
```
def fibonacci_recursive(n):
    print("Calculating F", "(", n, ")", sep="", end=", ")

    # Base case
    if n == 0:
        return 0
    elif n == 1:
        return 1

    # Recursive case
    else:
        return fibonacci_recursive(n-1) + fibonacci_recursive(n-2)
```

I guess it comes with practice but biggest hurdle of recursives is the risk of stack overflow. Python lacks tail-call elimination() a counter to stack overflow per the article:
```
>>> import sys
>>> sys.getrecursionlimit()
3000
```

### Pytest Fixtures and Coverage ([Article](https://www.linuxjournal.com/content/python-testing-pytest-fixtures-and-coverage))

I have to say this article was very helpful when it comes to testing basics. I need it immensely. I heven't been exposed to testing until this course. I'm still wrapping my head around it. 

The author speaks of fixtures and covereage. Fixtures are a combination of the ```pytest.fixture``` and the function definition.  An example per the article:

```
def reverse_lines(f):
   return [one_line.rstrip()[::-1] + '\n'
           for one_line in f]

```

Coverage is simpler. You want to provide a test suite that coves all or as many as possible usages for the function being tested. If it requires an integer? Test for that. If it cannot be negative, test for that.

### Bookmark/Skim

Pytest Fixtures ([Article](https://docs.pytest.org/en/latest/explanation/fixtures.html))

### Things I want to know more about

* 

Go [Home](index.md)