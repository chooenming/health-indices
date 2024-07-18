health-indices
==============

A unified collection of health indices and health indicators eg bmi, bai, corp index, etc.

Purpose of the Package
----------------------
- The purpose of the package is to provide a collection of all health indices in one unified library.

Features
--------
- Collection of Health Indices:
  - BMI
  - BAI
  - Corpulence Index
  - Piglet Indices
  - etc.
- Collection of Health Indicators:
  - Mortality rate
  - Birth rate
  - Prevalence rate
  - Fertility rate

Getting Started
---------------
The package can be found on PyPI hence you can install it using pip.

Installation
------------
.. code-block:: bash

    pip install health_indices

Usage
-----
Using the short forms or abbreviated forms of indices:

.. code-block:: python

    >>> from health_indices import bmi, bai
    >>> bmi(54, 1.70)

Using the long form of indices:

.. code-block:: python

    >>> from health_indices import bodymassindex
    >>> bodymassindex(54, 1.70)

Examples
--------
.. code-block:: python

    >>> from health_indices import bmi, bai
    >>> bmi(54, 1.70)
    Body Mass Index is => 18.0
    BMI Category => Underweight
    Body Mass Index is => 18.0
    18.0
    >>> a = bmi(54, 1.70)
    Body Mass Index is => 18.0
    BMI Category => Underweight
    Body Mass Index is => 18.0
    >>> a
    18.0
    >>>

Contribution
------------
Contributions are welcome.
Notice a bug? Let me know. Thanks.

Author
------
- Main Maintainer: Choo En Ming
- chooenming@gmail.com
