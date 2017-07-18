Installation
============

Prerequisites
-------------
`virtualenvwrapper <http://virtualenvwrapper.readthedocs.org/en/latest/install.html>`_
should be installed and configured in your environment.

Installing The Client
---------------------

The Faaspot python client called ``fas``.
Create a dedicated virtualenv for ``fas`` and install ``fas`` in that environment.

.. code-block:: sh

    $ mkvirtualenv faaspot
    $ pip install fas

.. note::
    Installing ``fas`` will provide both cli and python-client library.


Setting Up The Environment
--------------------------

Create a FaaSpot profile, that contains your FaaSpot token credentials.

.. code-block:: sh

    $ fas profiles create --token MY_API_TOKEN

The `fas profiles create` command will create a global configuration file located at ~/.faaspot,
which contain the connection configuration to FaaSpot.

