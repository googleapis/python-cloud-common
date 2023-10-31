:**NOTE**: **This github repository is archived. The repository contents and history have moved to** `google-cloud-python`_.

.. _google-cloud-python: https://github.com/googleapis/google-cloud-python/tree/main/packages/google-cloud-common


Python Client for Google Cloud Common
=====================================

|ga| |pypi| |versions|

This package contains generated Python types for `google.cloud.common`.

- `Client Library Documentation`_

.. |ga| image:: https://img.shields.io/badge/support-ga-gold.svg
   :target: https://github.com/googleapis/google-cloud-python/blob/main/README.rst#ga-support
.. |pypi| image:: https://img.shields.io/pypi/v/google-cloud-common.svg
   :target: https://pypi.org/project/google-cloud-common/
.. |versions| image:: https://img.shields.io/pypi/pyversions/google-cloud-common.svg
   :target: https://pypi.org/project/google-cloud-common/
.. _Client Library Documentation: https://cloud.google.com/python/docs/reference/common/latest

Installation
------------

Install this library in a `virtualenv`_ using pip. `virtualenv`_ is a tool to
create isolated Python environments. The basic problem it addresses is one of
dependencies and versions, and indirectly permissions.

With `virtualenv`_, it's possible to install this library without needing system
install permissions, and without clashing with the installed system
dependencies.

.. _`virtualenv`: https://virtualenv.pypa.io/en/latest/


Mac/Linux
^^^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    source <your-env>/bin/activate
    <your-env>/bin/pip install google-cloud-common


Windows
^^^^^^^

.. code-block:: console

    pip install virtualenv
    virtualenv <your-env>
    <your-env>\Scripts\activate
    <your-env>\Scripts\pip.exe install google-cloud-common
