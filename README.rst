doc
===

Document all the things!

Building the docs
=================

Make sure ``Sphinx`` is installed::

  virtualenv sphinx
  . sphinx/bin/activate
  pip install Sphinx

Activate your virtualenv and build::

  . sphinx/bin/activate
  pip install Sphinx
  make html

Python has a built-in webserver that makes it easy to view your local docs
build::

  cd build/html/
  python -m SimpleHTTPServer

This will start a web server at port 8000 with your build.
