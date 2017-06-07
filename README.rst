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
        | |scrutinizer|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/jira-stats/badge/?style=flat
    :target: https://readthedocs.org/projects/jira-stats
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/spascoe/jira-stats.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/spascoe/jira-stats

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/spascoe/jira-stats?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/spascoe/jira-stats

.. |requires| image:: https://requires.io/github/spascoe/jira-stats/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/spascoe/jira-stats/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/spascoe/jira-stats/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/spascoe/jira-stats

.. |codecov| image:: https://codecov.io/github/spascoe/jira-stats/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/spascoe/jira-stats

.. |version| image:: https://img.shields.io/pypi/v/jira-stats.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/jira-stats

.. |commits-since| image:: https://img.shields.io/github/commits-since/spascoe/jira-stats/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/spascoe/jira-stats/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/jira-stats.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/jira-stats

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/jira-stats.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/jira-stats

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/jira-stats.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/jira-stats

.. |scrutinizer| image:: https://img.shields.io/scrutinizer/g/spascoe/jira-stats/master.svg
    :alt: Scrutinizer Status
    :target: https://scrutinizer-ci.com/g/spascoe/jira-stats/


.. end-badges

An experimental JIRA Statistics generation package

* Free software: BSD license

Installation
============

::

    pip install jira-stats

Documentation
=============

https://jira-stats.readthedocs.io/

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
