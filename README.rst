Part of `edX code`__.

__ http://code.edx.org/

The isolation levels are changed only on MySQL.

Tests
-----

Setup the database:

.. code:: mysql

  CREATE DATABASE dbutils;
  CREATE USER 'dbutils'@'localhost' IDENTIFIED BY 'password';
  GRANT ALL PRIVILEGES ON *.* TO 'dbutils'@'localhost';
  CREATE DATABASE dbutils;

Install the python requirements:

.. code:: bash

  pip install -r requirements.txt


Run the tests:

.. code:: bash

  python runtests.py

License
-------

The code in this repository is licensed under version 3 of the AGPL unless
otherwise noted.

Please see ``LICENSE.txt`` for details.

How To Contribute
-----------------

Contributions are very welcome.

Please read `How To Contribute <https://github.com/edx/edx-platform/blob/master/CONTRIBUTING.rst>`_ for details.

Even though it was written with ``edx-platform`` in mind, the guidelines
should be followed for Open edX code in general.

Reporting Security Issues
-------------------------

Please do not report security issues in public. Please email security@edx.org

Mailing List and IRC Channel
----------------------------

You can discuss this code on the `edx-code Google Group`__ or in the
``edx-code`` IRC channel on Freenode.

__ https://groups.google.com/forum/#!forum/edx-code
