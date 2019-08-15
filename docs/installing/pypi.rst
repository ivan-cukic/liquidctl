The Pythonic way
~~~~~~~~~~~~~~~~

liquidctl can be installed by grabbing a `release from PyPI`_ with *pip*.

.. code-block:: none

   # pip install liquidctl
   # pip install liquidctl==1.2.0rc1

For currently under development features, pip can also be used to install the
latest snapshot of the official repository.

.. code-block:: none

   # pip install git+https://github.com/jonasmalacofilho/liquidctl

Contributors to the project’s code or documentation will want to manually clone
the repository and install liquidctl in editable mode.

.. code-block:: none

   $ git clone https://github.com/jonasmalacofilho/liquidctl
   $ cd liquidctl
   # pip install --editable .

Of course, in all cases a virtual environment can be used instead of installing
the package globally.

.. _release from PyPI: https://pypi.org/project/liquidctl/#history
