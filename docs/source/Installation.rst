Installation
============

Using pip::

    pip install ttp

Or clone from GitHub, unzip, navigate to folder and run::

    python setup.py install or python -m pip install .

Additional dependencies
-----------------------

TTP mainly uses built-in libraries. However, additional modules need to be installed on the system for certain features to work.

**Group Functions**

* :ref:`Groups/Functions:cerberus` - requires `Cerberus library <https://docs.python-cerberus.org/en/stable/>`_

**Output Formatters**

* :ref:`Outputs/Formatters:yaml` - requires `PyYAML module <https://pypi.org/project/PyYAML/>`_
* :ref:`Outputs/Formatters:tabulate` - requires `tabulate module <https://pypi.org/project/tabulate/>`_
* :ref:`Outputs/Formatters:jinja2` - requires `Jinja2 module <https://pypi.org/project/Jinja2/>`_
* :ref:`Outputs/Formatters:excel` - requires `openpyxl <https://openpyxl.readthedocs.io/en/stable/#>`_
* :ref:`Outputs/Formatters:N2G` - requires `N2G module <https://pypi.org/project/N2G/>`_

**Output Functions**

* :ref:`Outputs/Functions:deepdiff` - requires `deepdiff library <https://pypi.org/project/deepdiff/>`_

**Lookup Tables**

* INI lookup tables - requires `configparser <https://pypi.org/project/configparser/>`_
* :ref:`Lookup Tables/Lookup Tables:geoip2 database` - requires `GeoIP2  <https://pypi.org/project/geoip2/>`_
