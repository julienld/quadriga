.. quadriga documentation master file, created by
   sphinx-quickstart on Thu Mar 30 01:07:06 2017.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

**Quadriga** is a Python client for QuadrigaCX_, a Canadian cryptocurrency
exchange platform. It wraps `REST API v2`_ and facilitates the process of
trading Bitcoin_, Ethereum_ and Litecoin_.

.. _QuadrigaCX: https://www.quadrigacx.com
.. _REST API v2: https://www.quadrigacx.com/api_info
.. _Bitcoin: https://bitcoin.org/
.. _Ethereum: https://ethereum.org/
.. _Litecoin: https://litecoin.org/

.. image:: https://travis-ci.org/joowani/quadriga.svg?branch=master
    :target: https://travis-ci.org/joowani/quadriga

.. image:: https://badge.fury.io/py/quadriga.svg
    :target: https://badge.fury.io/py/quadriga
    :alt: Package version

.. image:: https://img.shields.io/badge/python-2.7%2C%203.4%2C%203.5%2C%203.6-blue.svg
    :target: https://github.com/joowani/quadriga
    :alt: Python Versions

.. image:: https://coveralls.io/repos/github/joowani/quadriga/badge.svg?branch=master
    :target: https://coveralls.io/github/joowani/quadriga?branch=master
    :alt: Test Coverage

.. image:: https://img.shields.io/github/issues/joowani/quadriga.svg
    :target: https://github.com/joowani/quadriga/issues
    :alt: Issues Open

.. image:: https://img.shields.io/badge/license-MIT-blue.svg
    :target: https://raw.githubusercontent.com/joowani/quadriga/master/LICENSE
    :alt: MIT License

|

Requirements
============

- Python 2.7.x, 3.4.x, 3.5.x or 3.6.x
- QuadrigaCX API secret, API key and client ID


Installation
============

To install a stable version from PyPi_:

.. code-block:: bash

    ~$ pip install quadriga


To install the latest version directly from GitHub_:

.. code-block:: bash

    ~$ pip install -e git+git@github.com:joowani/quadriga.git@master#egg=quadriga

Note: ``sudo`` may be required depending on the environment.

.. _PyPi: https://pypi.python.org/pypi/quadriga
.. _GitHub: https://github.com/joowani/quadriga


Contents
========

.. toctree::
    :maxdepth: 1

    intro
    api
    errors
    logging
    public
    contributing