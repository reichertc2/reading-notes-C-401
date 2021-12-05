# Code 401 - Advanced Software Development - Python

## Class 06 - Game of Greed

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### How to use Random Module ([Article](https://www.pythonforbeginners.com/random/how-to-use-the-random-module-in-python))

The random function looks to be fairly simple in use and useful to boot.  The randomness is useful for security purposes and for tabulating probability. The ways discussed in the article are as follows:

```
import random
from random import shuffle

random.randint(n,y)
# random integer betwen n and y

random.random()
# larger numbers for random

random.choice()
# select randomly of input (i.e. list)

random.randrange(n,y[,step])
# similar to randint but can be other than integer and can incorporate a step

shuffle(x)
# generate random number in a range, example in for loop
```

### What is Risk Analysis ([Article](https://www.edureka.co/blog/risk-analysis-in-software-testing/))

Risk analysis is the mitigation of unwanted effects. The mitigation comes from multiple areas. Including but not limited to the organization's toleration of risk.

There are risks inherent in every endeavor, software is no different. They come in many forms, as listed by the article, use of new hardware, use of new technology, use of automation tools, the sequence of code, and many others.

This article only mentions a high, medium, low risk table. In many companies this list is more comprehensive. Additionally, to the risk analysis itself, that is a study all its own. It should not be the only result based on executing something. Cost benefit analysis should be used in parallel.

### Test Coverage ([Article](https://martinfowler.com/bliki/TestCoverage.html))

As I use testing more and more, I'm finding it very useful. The main trouble for me is my dependence on ```print()``` or ```console.log()```.  This method of using the console to show you the errors is near instantaneous. The problem is that you are guessing what the outcome is. Its tantamount to shooting from the hip. 

Testing can and does bring uniformity and clarity to your code. As with everything measure needs to be managed. Coverage is no different. Coverage can be falsified with weak testing. It can be burdensome with lengthy testing. Either way there are ways to mitigate the risk/reward of testing. 

I would like to see more on the testing suites that show untested code.

### Videos

Big O Notation ([Video](https://www.youtube.com/watch?v=v4cd1O4zkGw))


### Bookmark/Skim

Python Random ([Article](https://docs.python.org/3/library/random.html))



### Additional Resources

What is Dependency Injection ([Article](https://www.freecodecamp.org/news/a-quick-intro-to-dependency-injection-what-it-is-and-when-to-use-it-7578c84fa88f/))


### Things I want to know more about

* 

Go [Home](index.md)