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
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/lusty/badge/?style=flat
    :target: https://readthedocs.org/projects/lusty
    :alt: Documentation Status

.. |travis| image:: https://api.travis-ci.org/ovalmoney/lusty.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/ovalmoney/lusty

.. |requires| image:: https://requires.io/github/ovalmoney/lusty/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/ovalmoney/lusty/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/ovalmoney/lusty/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/ovalmoney/lusty

.. |version| image:: https://img.shields.io/pypi/v/lusty.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/lusty

.. |wheel| image:: https://img.shields.io/pypi/wheel/lusty.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/lusty

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/lusty.svg
    :alt: Supported versions
    :target: https://pypi.org/project/lusty

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/lusty.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/lusty

.. |commits-since| image:: https://img.shields.io/github/commits-since/ovalmoney/lusty/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/ovalmoney/lusty/compare/v0.0.1...master



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
