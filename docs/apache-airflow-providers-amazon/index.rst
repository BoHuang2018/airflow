 .. Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

 ..   http://www.apache.org/licenses/LICENSE-2.0

 .. Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.

``apache-airflow-providers-amazon``
===================================

Content
-------

.. toctree::
    :maxdepth: 1
    :caption: Guides

    Connection types <connections/index>
    Operators <operators/index>
    Secrets backends <secrets-backends/index>
    Logging for Tasks <logging/index>

.. toctree::
    :maxdepth: 1
    :caption: References

    Python API <_api/airflow/providers/amazon/index>

.. toctree::
    :maxdepth: 1
    :caption: Resources

    Example DAGs <https://github.com/apache/airflow/tree/main/airflow/providers/amazon/aws/example_dags>
    PyPI Repository <https://pypi.org/project/apache-airflow-providers-amazon/>
    Installing from sources <installing-providers-from-sources>

.. THE REMAINDER OF THE FILE IS AUTOMATICALLY GENERATED. IT WILL BE OVERWRITTEN AT RELEASE TIME!


.. toctree::
    :maxdepth: 1
    :caption: Commits

    Detailed list of commits <commits>


Package apache-airflow-providers-amazon
------------------------------------------------------

Amazon integration (including `Amazon Web Services (AWS) <https://aws.amazon.com/>`__).


Release: 3.0.0

Provider package
----------------

This is a provider package for ``amazon`` provider. All classes for this provider package
are in ``airflow.providers.amazon`` python package.

Installation
------------

You can install this package on top of an existing Airflow 2.1+ installation via
``pip install apache-airflow-providers-amazon``

PIP requirements
----------------

============================  ===================
PIP package                   Version required
============================  ===================
``apache-airflow``            ``>=2.1.0``
``boto3``                     ``>=1.15.0,<2.0.0``
``jsonpath_ng``               ``>=1.5.3``
``pandas``                    ``>=0.17.1, <1.4``
``redshift_connector``        ``~=2.0.888``
``sqlalchemy_redshift``       ``~=0.8.6``
``watchtower``                ``~=2.0.1``
``mypy-boto3-rds``            ``>=1.21.0``
``mypy-boto3-redshift-data``  ``>=1.21.0``
============================  ===================

Cross provider package dependencies
-----------------------------------

Those are dependencies that might be needed in order to use all the features of the package.
You need to install the specified provider packages in order to use them.

You can install such cross-provider dependencies when installing from PyPI. For example:

.. code-block:: bash

    pip install apache-airflow-providers-amazon[apache.hive]


======================================================================================================================  ===================
Dependent package                                                                                                       Extra
======================================================================================================================  ===================
`apache-airflow-providers-apache-hive <https://airflow.apache.org/docs/apache-airflow-providers-apache-hive>`_          ``apache.hive``
`apache-airflow-providers-cncf-kubernetes <https://airflow.apache.org/docs/apache-airflow-providers-cncf-kubernetes>`_  ``cncf.kubernetes``
`apache-airflow-providers-exasol <https://airflow.apache.org/docs/apache-airflow-providers-exasol>`_                    ``exasol``
`apache-airflow-providers-ftp <https://airflow.apache.org/docs/apache-airflow-providers-ftp>`_                          ``ftp``
`apache-airflow-providers-google <https://airflow.apache.org/docs/apache-airflow-providers-google>`_                    ``google``
`apache-airflow-providers-imap <https://airflow.apache.org/docs/apache-airflow-providers-imap>`_                        ``imap``
`apache-airflow-providers-mongo <https://airflow.apache.org/docs/apache-airflow-providers-mongo>`_                      ``mongo``
`apache-airflow-providers-salesforce <https://airflow.apache.org/docs/apache-airflow-providers-salesforce>`_            ``salesforce``
`apache-airflow-providers-ssh <https://airflow.apache.org/docs/apache-airflow-providers-ssh>`_                          ``ssh``
======================================================================================================================  ===================

Downloading official packages
-----------------------------

You can download officially released packages and verify their checksums and signatures from the
`Official Apache Download site <https://downloads.apache.org/airflow/providers/>`_

* `The apache-airflow-providers-amazon 3.0.0 sdist package <https://downloads.apache.org/airflow/providers/apache-airflow-providers-amazon-3.0.0.tar.gz>`_ (`asc <https://downloads.apache.org/airflow/providers/apache-airflow-providers-amazon-3.0.0.tar.gz.asc>`__, `sha512 <https://downloads.apache.org/airflow/providers/apache-airflow-providers-amazon-3.0.0.tar.gz.sha512>`__)
* `The apache-airflow-providers-amazon 3.0.0 wheel package <https://downloads.apache.org/airflow/providers/apache_airflow_providers_amazon-3.0.0-py3-none-any.whl>`_ (`asc <https://downloads.apache.org/airflow/providers/apache_airflow_providers_amazon-3.0.0-py3-none-any.whl.asc>`__, `sha512 <https://downloads.apache.org/airflow/providers/apache_airflow_providers_amazon-3.0.0-py3-none-any.whl.sha512>`__)

.. include:: ../../airflow/providers/amazon/CHANGELOG.rst
