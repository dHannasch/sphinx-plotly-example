========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - |
        |
    * - package
      - | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/sphinx-plotly-example/badge/?style=flat
    :target: https://readthedocs.org/projects/sphinx-plotly-example
    :alt: Documentation Status

.. |commits-since| image:: https://img.shields.io/github/commits-since/dHannasch/sphinx-plotly-example/v0.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/dHannasch/sphinx-plotly-example/compare/v0.0.0...master



.. end-badges

An example package. Generated with cookiecutter-pylibrary.

Installation
============

::

    pip install sphinx-plotly-example

You can also install the in-development version with::

    pip install https://github.com/dHannasch/sphinx-plotly-example/archive/master.zip


Documentation
=============


https://sphinx-plotly-example.readthedocs.io/


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
