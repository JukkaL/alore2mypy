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

<pre>
  $ export ALOREPATH=/usr/local/share/alore/check
</pre>

TODO: Windows equivalent

Running tests
-------------

<pre>
 $ cd check
 $ alore test.alo
</pre>

Performing a conversion
-----------------------

<pre>
 $ cd check
 $ alore pgen.alo ALOREFILE
</pre>

Note that at the moment this just dumps the file to stdout in a human-readable
form, but does not actually generate working programs.