.. _install:

Installation
============

This documents explains how to install and configure Scrapyd, to deploy and run
your Scrapy spiders.

.. warning::

    This documentation is for the old |version| version of scrapyd.
    Unless you are maintaining an old project that requires it,
    you may instead want the
    `latest version <http://scrapyd.readthedocs.org/en/latest/>`_.

Requirements
------------

Scrapyd depends on the following libraries, but the installation process
takes care of installing the missing ones:

* Python 2.7 or above
* Twisted 8.0 or above
* Scrapy 1.0 or above
* six

Installing Scrapyd (generic way)
--------------------------------

How to install Scrapyd depends on the platform you're using. The generic way is
to install it from PyPI::

    pip install scrapyd
