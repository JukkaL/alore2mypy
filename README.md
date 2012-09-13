alore2mypy
==========

This is a tool for converting Alore code to mypy (http://www.mypy-lang.org/).

Setup
-----

You need Alore to run the program. The latest version from the git repo master
is the one most likely to work (http://www.alorelang.org/).

You you must include the "check" directory in the Alore distribution in your
Alore module search path. For example, if you have installed Alore under
/usr/local:

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

Note that at the moment this just dumps the file to stdout in a human-readable
form, but does not actually generate working programs.