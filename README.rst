========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-scanparam/badge/?style=flat
    :target: https://readthedocs.org/projects/python-scanparam
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/tclick/python-scanparam.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/tclick/python-scanparam

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/tclick/python-scanparam?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/tclick/python-scanparam

.. |requires| image:: https://requires.io/github/tclick/python-scanparam/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/tclick/python-scanparam/requirements/?branch=master

.. |codecov| image:: https://codecov.io/github/tclick/python-scanparam/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/tclick/python-scanparam

.. |version| image:: https://img.shields.io/pypi/v/scanparam.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/scanparam

.. |commits-since| image:: https://img.shields.io/github/commits-since/tclick/python-scanparam/v1.0.0.svg
    :alt: Commits since latest release
    :target: https://github.com/tclick/python-scanparam/compare/v1.0.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/scanparam.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/scanparam

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/scanparam.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/scanparam

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/scanparam.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/scanparam


.. end-badges

Scan a CHARMM parameter library for existing parameters.

* Free software: BSD 3-Clause License

Installation
============

::

    pip install scanparam

Documentation
=============

https://python-scanparam.readthedocs.io/

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
