===============
pytest-pastebin
===============

.. image:: https://img.shields.io/pypi/v/pytest-pastebin.svg
    :target: https://pypi.org/project/pytest-pastebin
    :alt: PyPI version

.. image:: https://github.com/pytest-dev/pytest-pastebin/actions/workflows/main.yml/badge.svg
    :target: https://github.com/pytest-dev/pytest-pastebin/actions/workflows/main.yml
    :alt: See Build Status on GitHub Actions

Submit pytest failure or test session information to a pastebin service.

The pastebin service used is `https://bpa.st/`__.

This plugin has been extracted from pytest's core in version 9.1.0.


Installation
------------

You can install "pytest-pastebin" via `pip`_ from `PyPI`_::

    $ pip install pytest-pastebin


Usage
-----

```
$ pytest --pastebin=failed  # Send failed info to bpa.st pastebin service
...
pastebin session-log: https://bpa.st/show/QUUX

$ pytest --pastebin=all     # Send all info to bpa.st pastebin service
...
pastebin session-log: https://bpa.st/show/THUD
```


License
-------

Distributed under the terms of the `MIT`_ license, "pytest-pastebin" is free and open source software.


Issues
------

If you encounter any problems, please `file an issue`_ along with a detailed description.

.. _`MIT`: https://opensource.org/licenses/MIT
.. _`pytest`: https://github.com/pytest-dev/pytest
.. _`pip`: https://pypi.org/project/pip/
.. _`PyPI`: https://pypi.org/project
