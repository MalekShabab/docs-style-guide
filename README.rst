.. _index:

****************
docs-style-guide
****************

`Pylons Project Documentation Style Guide <https://docs.pylonsproject.org/projects/docs-style-guide/>`_

This project is the style guide for documentation of all projects under the Pylons Project.



.. _contributing:

Contributing
============

See `contributing.md <https://github.com/Pylons/docs-style-guide/blob/master/contributing.md>`_.


.. _installation:

Installation
============

.. code-block:: bash

    # Check out the project.
    git clone https://github.com/Pylons/docs-style-guide.git
    # Change your working directory to the project.
    cd docs-style-guide
    # Create a virtual environment.
    python3 -m venv env
    # Install the project in development mode.
    env/bin/pip install -e .


.. _building-documentation:

Building documentation
======================

We use tox to build the documentation and run tests.
Install tox into your user space or virtual environment.

From the project root, run tox to build the documentation in HTML format.

.. code-block:: bash

    tox -e html

When the build finishes, you'll find HTML documentation rendered in `.tox/html`.

To build all formats of the documentation, omit arguments.

.. code-block:: bash

    tox
