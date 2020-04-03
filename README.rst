========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |requires|
        | |coveralls|

.. |docs| image:: https://readthedocs.org/projects/lusty/badge/?style=flat
    :target: https://readthedocs.org/projects/lusty
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/ovalmoney/lusty.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/ovalmoney/lusty

.. |requires| image:: https://requires.io/github/OvalMoney/lusty/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/OvalMoney/lusty/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/github/OvalMoney/lusty/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/github/OvalMoney/lusty



.. end-badges

A python DynamoDB data mapper

* Free software: MIT license

Installation
============

::

    pip install lusty

You can also install the in-development version with::

    pip install https://github.com/ovalmoney/lusty/archive/master.zip


Documentation
=============


https://lusty.readthedocs.io/


Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
