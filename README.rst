`book-club build`
=================
`book_club` is a little python tool used to automate the upkeep of my book
club.

All you need to do is update the appropriate variables in the book-club.yml
file and run `book-club build`. It'll generate an index.html file and you're
good to go.

Installation:
-------------

.. code::

    in theory you just run this:
    $ pip install git+https://github.com/ElijahCaine/book_club.git
    but that's broken right now due to an ImportError which I am actively fixing *right now*.

Setup
-----
Here's what your directory structure should look like

.. code::

    yourdomain.bla/
        bookclub/
            book-club.yml
            style.css
            template.jinja

`bookclub` is however you want to call `yourdomain.ext/bookclub/`.

For an exmample of book-club.yml, template.jinja, and style.css check out the
ones in this repo.
