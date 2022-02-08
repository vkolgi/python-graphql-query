========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |github-actions|
        |
    * - package
      - | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/python-graphql-query/badge/?style=flat
    :target: https://python-graphql-query.readthedocs.io/
    :alt: Documentation Status

.. |github-actions| image:: https://github.com/vkolgi/python-graphql-query/actions/workflows/github-actions.yml/badge.svg
    :alt: GitHub Actions Build Status
    :target: https://github.com/vkolgi/python-graphql-query/actions

.. |commits-since| image:: https://img.shields.io/github/commits-since/vkolgi/python-graphql-query/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/vkolgi/python-graphql-query/compare/v0.0.0...main



.. end-badges

This converts python dictionary into a Graphql Query.

* Free software: MIT license

Installation
============

::

    pip install python-graphql-query

You can also install the in-development version with::

    pip install https://github.com/vkolgi/python-graphql-query/archive/main.zip


Documentation
=============


https://python-graphql-query.readthedocs.io/


Development
===========

To run all the tests run::

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
