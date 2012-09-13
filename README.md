alore2mypy
==========

This is a tool for converting Alore code to mypy (http://www.mypy-lang.org/).

Setup
-----

You you must include the "check" directory in the Alore distribution in your
Alore path. For example, if you have installed Alore under /usr/local:

  $ export ALOREPATH=/usr/local/share/alore/check

TODO: Windows equivalent

Running tests
-------------

 $ cd check
 $ alore test.alo

Performing a conversion
-----------------------

 $ cd check
 $ alore pgen.alo ALOREFILE
