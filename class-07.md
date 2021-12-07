# Code 401 - Advanced Software Development - Python

## Class 07 - Game of Greed 2

Block intro

<!-- > An investment in knowledge pays the best interest. –  Benjamin Franklin -->


### Python Scope ([Article](https://realpython.com/python-scope-legb-rule/))

Global versus nonlocal in the relation of scope. What is the difference?

Global statements are ones declared a the top of the module outside of functions or are default values assigned by Python. They are reassignable, but this is not recommended. A good check on some of the global variables inside of python is by ```dir()```. I'm guessing this is shorthand for directory of global variables. As per the article it is unwise to rename default global variables as they will create bug riddled code and can break it entirely if you try to execute a default value after it's been reassigned.

Nonlocal variables can be accessed inside of functions and not reassigned inside of functions. These are associated with variables inside functions but are not directly associated with the actions in the present function. It applies more for the variables outside of nested functions. Nested functions can use these variables and values, but they cannot natively modify them. Not without the use of ```nonlocal``` preceding the variable in question.

I was  familiar with this concept, but now I have terms and syntax to go with the concept.


### Video

Don’t be CONFUSED by BIG O notation anymore! ([Video](https://www.youtube.com/watch?v=5Uqawfl0VHQ))

### Bookmark/Skim

Rolling Dice Examples ([Article](https://artofproblemsolving.com/wiki/index.php/Basic_Programming_With_Python#Program_Example_1_3))

### Things I want to know more about

* 

Go [Home](index.md)