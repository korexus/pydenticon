Testing
=======

Pydenticon includes a number of unit tests which are used for regression
testing. The tests are fairly comprehensive, and also include comparison of
Pydenticon-generated identicons against a couple of samples generated by Sigil.

Tests depend on the following additional libraries:

* `Mock <https://pypi.python.org/pypi/mock/>`_

Test dependencies will be automatically downloaded when running the tests if
they're not present.

Pydenticon tests can be run with the following command::

  python setup.py test
