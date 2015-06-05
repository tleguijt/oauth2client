[![Build Status](https://travis-ci.org/google/oauth2client.svg?branch=master)](https://travis-ci.org/google/oauth2client)

[![Coverage Status](https://img.shields.io/coveralls/google/oauth2client.svg)](https://coveralls.io/r/google/oauth2client?branch=master)

[Fork info]
This fork has been adjusted to play well with the Django modifications on the six libarary.
Some imports aren't available when running in Django, since Django modifies the import paths of the six library

[Description]

This is a client library for accessing resources protected by OAuth 2.0.

[Full documentation](http://google.github.io/oauth2client/)

Installation
============

To install, simply say

    $ pip install --upgrade oauth2client

Contributing
============

Please see the
[contributing page](http://google.github.io/oauth2client/contributing.html)
for more information. In particular, we love pull requests -- but please make
sure to sign the contributor license agreement.

Supported Python Versions
=========================

We support Python 2.6, 2.7, 3.3+. More information
[in the docs](http://google.github.io/oauth2client/#supported-python-versions).
