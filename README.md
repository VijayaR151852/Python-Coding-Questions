# Python

#Modules and Packages

A file containing a set of functions you want to include in your application.

Create a Module:

To create a module just save the code you want in a file with the file extension .py:
Example
Save this code in a file named mymodule.py

Use a Module:

Now we can use the module we just created, by using the import statement:
Example
Import the module named mymodule, and call the greeting function:

import mymodule

Built-in Modules:

There are several built-in modules in Python, which you can import whenever you like.

import datetime   
import json      
import math



Q1 = "select count(id) from movie where year < 2000;"

Q2 = "select avg(rank) from movie where year = 1991;"

Q3 = "select min(rank) from movie where year = 1991;"

Q4 = "select fname,lname from actor inner join cast on actor.id = pid where mid = 27;"

Q5 = "select count(mid) from cast inner join actor on actor.id = pid where fname = 'Jon' and lname = 'Dough';"

Q6 = "select name from movie where name like 'Young Latin Girls%' and year between 2003 and 2006;"

Q7 = "select distinct fname,lname from director inner join moviedirector on id = did where mid in (313396,313404,313413,313421,313443);"

Q8 = "select movie.id,movie.name,movie.year,movie.rank from movie inner join moviedirector on movie.id = mid natural join cast where (did = 13407 and pid = 80684) order by movie.name Asc;"

Q9 = "select fname,lname from director inner join moviedirector on director.id = did inner join movie on mid = movie.id group by mid having count(mid) >= 4 and movie.year = 2001;"

Q10 = "select gender, count(gender = 'm') from actor group by gender order by gender Asc;"

Q11 = ""

Q12 = ""

Q13 = ""
