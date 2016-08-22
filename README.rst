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
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/python-appsembler-flow/badge/?style=flat
    :target: https://readthedocs.org/projects/python-appsembler-flow
    :alt: Documentation Status

.. |version| image:: https://img.shields.io/pypi/v/appsembler-flow.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/appsembler-flow

.. |downloads| image:: https://img.shields.io/pypi/dm/appsembler-flow.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/appsembler-flow

.. |wheel| image:: https://img.shields.io/pypi/wheel/appsembler-flow.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/appsembler-flow

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/appsembler-flow.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/appsembler-flow

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/appsembler-flow.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/appsembler-flow


.. end-badges

Appsembler + Git Flow

* Free software: BSD license

Installation
============

::

    pip install appsembler-flow

Documentation
=============

https://python-appsembler-flow.readthedocs.io/

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
