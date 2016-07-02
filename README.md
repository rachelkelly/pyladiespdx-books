## LibrarPy
#### *A webapp to track technical library lending amongst Portland PyLadies*

I. Purpose and Introduction
II. Code of Conduct
III. What has been done
IV. What needs doing
V. Recommended Tutorials

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

### III. What has been done
 * Initial database setup
 * Heroku webapp creation and linkage
 * Virtualenv creation and complete `requirements.txt`
 * Views (in the sense of what the pages will look like) begun
 * Stylesheet
 * Capacity to add new books with genuine connection to database
 * HTML-capable, DB-drawn list of books
 * Adapted [Contributor Covenant](http://contributor-covenant.org/) for CODE_OF_CONDUCT.md

### IV. What NEEDS doing
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
 * Add a FOSS license, I suggest [GPL 2](https://www.gnu.org/licenses/old-licenses/gpl-2.0), 
mostly because it has good support and has been around a while.

### V. Tutorials
Please note, you do not have to do any of these to contribute if you feel happy and familiar 
with them, but if you want to learn more about these things here are some resources that have 
been battle-tested by a bunch of us here at PyLadies PDX
 * [Djangogirls Python Tutorial](http://tutorial.djangogirls.org/en/index.html), which starts at the beginning and introduces Python.  Please learn as much as you'd like to of the Django portion Django, which is another kind of Python web framework like Flask is, which means some of it will be different, but which also uses the foundational structure of Model View Controller.
 * [Miguel Grinberg's Flask tutorial](http://blog.miguelgrinberg.com/post/the-flask-mega-tutorial-part-i-hello-world)
 * Codecademy's [HTML/CSS beginner tutorial](https://www.codecademy.com/learn/web).  Their [Make A Website](https://www.codecademy.com/learn/make-a-website).
 * [The Official PostgreSQL Tutorial](http://www.postgresql.org/docs/9.4/static/tutorial.html)
