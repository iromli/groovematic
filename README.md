Groovematic
===========

The source code behind my [personal website](http://groovematic.com/).
It's [unlicensed](http://unlicense.org/) anyway.

Requirements
------------

Python libraries:

    $ pip install -r requirements.txt

`sassc` executable is available at https://github.com/sass/sassc (requires https://github.com/sass/libsass).

Hacking
-------

Compile and serve the content at `http://localhost:8000/`:

    $ acrylamid autocompile

Deploy:

    $ acrylamid deploy
