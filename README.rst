===========================
cookiecutter-python-package
===========================

This is a Cookiecutter template for a Python package that tries to follow the current best practices from the `Python Packaging User Guide`_ while including configuration for some helpful extra tools.

This is a fork of https://github.com/audreyr/cookiecutter-pypackage and https://github.com/tylerdave/cookiecutter-python-package .

See https://github.com/audreyr/cookiecutter for instructions for using Cookiecutter.

The new project will be configured with the following by default:

* Free software: MIT license
* Vanilla testing setup with `unittest` and `python setup.py test`
* (TBD) Example/Doc based CLI / cmdln by DocOpt_ and setup entries
* (TBD) Example/Doc based testing by XDocTest_
* Sphinx_ docs: Documentation ready for generation with, for example, ReadTheDocs_
* Tox_ testing: Setup to easily test for Python 3.3, 3.4, 3.5, pypy
* Travis-CI_: Ready for Travis Continuous Integration testing

Usage
-----

Generate a Python package project::

    cookiecutter https://github.com/tylerdave/cookiecutter-python-package.git

Then:

* Create a repo and put it there.
* Add the repo to your Travis CI account.
* Add the repo to your ReadTheDocs account + turn on the ReadTheDocs service hook.
* Release your package the standard Python way. Here's a release checklist:  https://gist.github.com/audreyr/5990987

Not Exactly What You Want? See similar cookiecutter templates in the earlier repos.

.. _Sphinx: http://sphinx-doc.org/
.. _ReadTheDocs: https://readthedocs.org/
.. _`Python Packaging User Guide`: https://packaging.python.org/en/latest/index.html
.. _DocOpt: https://pypi.org/project/docopt/
.. _XDocTest: https://pypi.org/project/xdoctest/
.. _Tox: http://testrun.org/tox/
.. _Travis-CI: http://travis-ci.org/

