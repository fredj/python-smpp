Python SMPP
===========

An SMPP version 3.4 library written in Python, suitable for use in [Twisted][twisted]

To get started with development:

    $ virtualenv --no-site-packges ve/
    $ source ve/bin/activate
    (ve)$ pip install -r requirements.pip
    (ve)$ python setup.py develop
    (ve)$ python
    >>> import smpp
    >>>

Run the tests with nose

    (ve)$ nosetests

[twisted]: http://www.twistedmatrix.com