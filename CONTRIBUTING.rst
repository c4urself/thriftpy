How to contribute
=================

1. Fork the repo and make changes.

2. Write a test which shows a bug was fixed or the feature works as expected.

3. Make sure ``travis-ci`` or ``tox`` tests succeed.

4. Send pull request.


### Testing
===========

Run a virtualenv or similar, then:

.. code:: bash

    $ pip install cython tox

Then run the tests from the root of the repo:

.. code:: bash

    $ tox
