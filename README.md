## LibrarPy
#### *A webapp to track technical library lending amongst Portland PyLadies*

I. Purpose and Introduction  
II. Code of Conduct  
III. How to get started  
IV. What has been done  
V. What needs doing  
VI. Recommended Tutorials  
VII. Attribution  

### I. Purpose and Introduction
The purpose of the app is to manage the vast quantity of technical books which the PyLadies
have been given, or books which members own and are happy to lend.  We estimate that that
number of books exceeds a hundred, and once people start adding theirs that number will
only increase.

This is a webapp written with the web framework [Flask](http://flask.pocoo.org/)
using primarily Python as well as HTML and CSS, which includes the [Skeleton](http://getskeleton.com/)
stylesheet.  There is also a touch of Jinja2 for templating (squishing formatting stuff into
Python) as well as PostgreSQL for the database.  As of the publication of this document
(30 April 2016), the barest function of it works, which includes adding a book and seeing a
list of all books available.

### II. Code of Conduct
So you want to contribute!  AMAZING, THANK YOU.  Please see our [Code of Conduct](https://github.com/rachelkelly/pyladiespdx-books/blob/contribution/CODE_OF_CONDUCT.md) before jumping
in; first and foremost we are trying to make this a safe space for PyLadies to hack and code
and work together.  Further, we are looking for contributions from women only, inclusive of trans women.

### III. How to get started
First you'll want to pull down this git repository, which contains this README and all the code.
If you have not used Git or Github before, welcome!  We've got a tutorial for you (listed below in the Tutorials section) and we'd love
to help you in person too at our Saturday Code and Learn events.

First, with your Github account, fork the repo.

![hit the fork button! yay](https://github.com/rachelkelly/pyladiespdx-books/fork.png "Fork image")

```
git clone git@github.com:rachelkelly/pyladiespdx-books.git
```

### IV. What has been done
 * Initial database setup
 * Heroku webapp creation and linkage
 * Virtualenv creation and complete `requirements.txt`
 * Views (in the sense of what the pages will look like) begun
 * Stylesheet
 * Capacity to add new books with genuine connection to database
 * HTML-capable, DB-drawn list of books
 * MIT license added
 * Adapted [Contributor Covenant](http://contributor-covenant.org/) for CODE_OF_CONDUCT.md

### V. What NEEDS doing
 * probably always cleaning up this document :)
 * change to Bootstrap CSS instead of Skeleton - it is more full-featured
 * Authorization (this has been started)
 * List of books by holder
 * Logged-in user can request a book
 * Transfer ownership of book (a. user requests book. b. owner says ok. c. owner says "ok the book is in their hands"  or some such process)
 * Set up email alerts for book requests
 * Set up email reminders two weeks (or some number of weeks!)
   * both of these can be done with smtp python modules probably!
 * Write a list of rules
 * Tests

### VI. Tutorials
Please note, you do not have to do any of these to contribute if you feel happy and familiar 
with them, but if you want to learn more about these things here are some resources that have 
been battle-tested by a bunch of us here at PyLadies PDX
 * [Djangogirls Python Tutorial](http://tutorial.djangogirls.org/en/index.html), which starts at the beginning and introduces Python.  Please learn as much as you'd like to of the Django portion Django, which is another kind of Python web framework like Flask is, which means some of it will be different, but which also uses the foundational structure of Model View Controller.
 * [Miguel Grinberg's Flask tutorial](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
 * Codecademy's [HTML/CSS beginner tutorial](https://www.codecademy.com/learn/web).  Their [Make A Website](https://www.codecademy.com/learn/make-a-website).
 * [The Official PostgreSQL Tutorial](http://www.postgresql.org/docs/9.4/static/tutorial.html)
 * [First introduction to Github](https://guides.github.com/activities/hello-world/)
 * [Further introduction to Git](http://gitimmersion.com/), the underlying tool behind modern source control - you can get as in depth or referential with this as you like.
 * [exercism](http://www.exercism.io) as a way to get started understanding how tests work and as samples for how to write them, and how to write FOR them.  Particularly we recommend the [Python exercism track](http://exercism.io/languages/python), though many of the languages' problem sets are good.

### VII. Attribution
This app was originally created by Juliana Arrighi and Rachel Kelly in 2014.
Code of Conduct adapted from Coraline Ada Ehmke's [Contributor Covenant])(http://contributor-covenant.org/).
PyLadies PDX is the Portland arm of the international women's group PyLadies, a group of women Python programmers.  Find out more at our [Meetup](http://www.meetup.com/PyLadies-PDX/).
