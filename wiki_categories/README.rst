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
        | |coveralls| |codecov|
        | |codacy| |codeclimate|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|
.. |docs| image:: https://readthedocs.org/projects/wiki_categories/badge/?style=flat
    :target: https://readthedocs.org/projects/wiki_categories
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/ckot/wiki_categories.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/ckot/wiki_categories

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/ckot/wiki_categories?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/ckot/wiki_categories

.. |requires| image:: https://requires.io/github/ckot/wiki_categories/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/ckot/wiki_categories/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/ckot/wiki_categories/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/ckot/wiki_categories

.. |codecov| image:: https://codecov.io/github/ckot/wiki_categories/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/ckot/wiki_categories

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg
    :target: https://www.codacy.com/app/ckot/wiki_categories
    :alt: Codacy Code Quality Status

.. |codeclimate| image:: https://codeclimate.com/github/ckot/wiki_categories/badges/gpa.svg
   :target: https://codeclimate.com/github/ckot/wiki_categories
   :alt: CodeClimate Quality Status

.. |version| image:: https://img.shields.io/pypi/v/wiki-categories.svg
    :alt: PyPI Package latest release
    :target: https://pypi.org/project/wiki-categories

.. |commits-since| image:: https://img.shields.io/github/commits-since/ckot/wiki_categories/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/ckot/wiki_categories/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/wiki-categories.svg
    :alt: PyPI Wheel
    :target: https://pypi.org/project/wiki-categories

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/wiki-categories.svg
    :alt: Supported versions
    :target: https://pypi.org/project/wiki-categories

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/wiki-categories.svg
    :alt: Supported implementations
    :target: https://pypi.org/project/wiki-categories


.. end-badges

A python library for extracting both text and the category hierarchy from wikimedia dump files

* Free software: Apache Software License 2.0

Installation
============

::

    pip install wiki-categories

Documentation
=============


https://wiki_categories.readthedocs.io/


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
