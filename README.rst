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
.. |docs| image:: https://readthedocs.org/projects/af2slurm/badge/?style=flat
    :target: https://af2slurm.readthedocs.io/
    :alt: Documentation Status

.. |commits-since| image:: https://img.shields.io/github/commits-since/ajasja/af2slurm/v0.0.1.svg
    :alt: Commits since latest release
    :target: https://github.com/ajasja/af2slurm/compare/v0.0.1...main



.. end-badges

Submit AF2 colab fold jobs to slurm

* Free software: GNU Lesser General Public License v3 or later (LGPLv3+)

Installation
============

::

    pip install af2slurm

You can also install the in-development version with::

    pip install https://github.com/ajasja/af2slurm/archive/main.zip


Documentation
=============


https://af2slurm.readthedocs.io/


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
