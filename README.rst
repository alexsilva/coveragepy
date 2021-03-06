.. Licensed under the Apache License: http://www.apache.org/licenses/LICENSE-2.0
.. For details: https://bitbucket.org/ned/coveragepy/src/default/NOTICE.txt

===========
Coverage.py
===========

Code coverage testing for Python.

|  |license| |versions| |status| |docs|
|  |ci-status| |win-ci-status| |codecov|
|  |kit| |format| |saythanks|

.. downloads badge seems to be broken... |downloads|

Coverage.py measures code coverage, typically during test execution. It uses
the code analysis tools and tracing hooks provided in the Python standard
library to determine which lines are executable, and which have been executed.

Coverage.py runs on many versions of Python:

* CPython 2.6, 2.7 and 3.3 through 3.7.
* PyPy2 5.6 and PyPy3 5.5.
* Jython 2.7.1, though not for reporting.
* IronPython 2.7.7, though not for reporting.

Documentation is on `Read the Docs`_.  Code repository and issue tracker are on
`Bitbucket`_, with a mirrored repository on `GitHub`_.

.. _Read the Docs: http://coverage.readthedocs.io
.. _Bitbucket: https://bitbucket.org/ned/coveragepy
.. _GitHub: https://github.com/nedbat/coveragepy


**New in 4.4:** Suppressable warnings, continuous coverage measurement.

New in 4.3: HTML ``--skip-covered``, sys.excepthook support, tox.ini
support.

New in 4.2: better support for multiprocessing and combining data.

New in 4.1: much-improved branch coverage.

New in 4.0: ``--concurrency``, plugins for non-Python files, setup.cfg
support, --skip-covered, HTML filtering, and more than 50 issues closed.


Getting Started
---------------

See the `Quick Start section`_ of the docs.

.. _Quick Start section: http://coverage.readthedocs.io/#quick-start


Contributing
------------

See the `Contributing section`_ of the docs.

.. _Contributing section: http://coverage.readthedocs.io/en/latest/contributing.html


License
-------

Licensed under the `Apache 2.0 License`_.  For details, see `NOTICE.txt`_.

.. _Apache 2.0 License: http://www.apache.org/licenses/LICENSE-2.0
.. _NOTICE.txt: https://bitbucket.org/ned/coveragepy/src/default/NOTICE.txt


.. |ci-status| image:: https://travis-ci.org/nedbat/coveragepy.svg?branch=master
    :target: https://travis-ci.org/nedbat/coveragepy
    :alt: Build status
.. |win-ci-status| image:: https://ci.appveyor.com/api/projects/status/kmeqpdje7h9r6vsf/branch/master?svg=true
    :target: https://ci.appveyor.com/project/nedbat/coveragepy
    :alt: Windows build status
.. |docs| image:: https://readthedocs.org/projects/coverage/badge/?version=latest&style=flat
    :target: http://coverage.readthedocs.io
    :alt: Documentation
.. |reqs| image:: https://requires.io/github/nedbat/coveragepy/requirements.svg?branch=master
    :target: https://requires.io/github/nedbat/coveragepy/requirements/?branch=master
    :alt: Requirements status
.. |kit| image:: https://badge.fury.io/py/coverage.svg
    :target: https://pypi.python.org/pypi/coverage
    :alt: PyPI status
.. |format| image:: https://img.shields.io/pypi/format/coverage.svg
    :target: https://pypi.python.org/pypi/coverage
    :alt: Kit format
.. |downloads| image:: https://img.shields.io/pypi/dw/coverage.svg
    :target: https://pypi.python.org/pypi/coverage
    :alt: Weekly PyPI downloads
.. |versions| image:: https://img.shields.io/pypi/pyversions/coverage.svg
    :target: https://pypi.python.org/pypi/coverage
    :alt: Python versions supported
.. |status| image:: https://img.shields.io/pypi/status/coverage.svg
    :target: https://pypi.python.org/pypi/coverage
    :alt: Package stability
.. |license| image:: https://img.shields.io/pypi/l/coverage.svg
    :target: https://pypi.python.org/pypi/coverage
    :alt: License
.. |codecov| image:: http://codecov.io/github/nedbat/coveragepy/coverage.svg?branch=master&precision=2
    :target: http://codecov.io/github/nedbat/coveragepy?branch=master
    :alt: Coverage!
.. |saythanks| image:: https://img.shields.io/badge/saythanks.io-%E2%98%BC-1EAEDB.svg
    :target: https://saythanks.io/to/nedbat
    :alt: Say thanks :)
