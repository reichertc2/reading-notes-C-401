# Code 401 - Advanced Software Development - Python

## Class 17 - Web Scraping

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### Web Scrape with Python in 4 minutes ([Article](https://towardsdatascience.com/how-to-web-scrape-with-python-in-4-minutes-bc49186a8460))

Such a simple concept, and a huge time saver. Web scraping is an automated process allows the user to compile data from a designated website. This site demonstrates on the New York MTA turnstile data. Some of the packages used are:
```
import requests
import urllib.request
import time
from bs4 import BeautifulSoup
```

The next task is to target your information, with this site it is links. Utilizing BeautifulSoup, the hunt for ```<a>```s begins. and through a couple of steps the url is exrtacted and usable. The next is a caution to utilize a delay function ```time.sleep(1)```, otherwise the site might register you as a spammer, from your multiple and rapid hits, like in a for loop.

Pretty neat stuff.

### What is Web Scraping? ([Article](https://en.wikipedia.org/wiki/Web_scraping))

Web scraping is useful. As per the website, the legality of it is still under debate. In most of the cases where it was a legal issue, the defendant was a for profit entity. Private not-for-profit ventures into web scraping seems legal. Though I'd have to dive deeper into those cases. For now, I would limit it and read the terms and conditions.

### How to scrape websites without getting blocked ([Article](https://www.scrapehero.com/how-to-prevent-getting-blacklisted-while-scraping/))

Being neighborly is very important to not getting clocked. As mentioned, there are multiple ways to mask your source IP and continuously bombard the site, but the trackers for bots are getting more and more advanced at detection. So in short, it is a good idea to write a bot to act more human than a computer.

Fun times ahead.

### Additional Resources

Track Amazon Prices ([Video](https://www.youtube.com/watch?v=Bg9r_yLk7VY))

### Bookmark/Skim

Beautiful Soup ([Article](https://www.crummy.com/software/BeautifulSoup/))

### Things I want to know more about

* 

Go [Home](index.md)