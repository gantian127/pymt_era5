=========
pymt_era5
=========

.. image:: https://zenodo.org/badge/DOI/10.5281/zenodo.10368880.svg
        :target: https://zenodo.org/doi/10.5281/zenodo.10368880

.. image:: https://img.shields.io/badge/CSDMS-Basic%20Model%20Interface-green.svg
        :target: https://bmi.readthedocs.io/
        :alt: Basic Model Interface

.. .. image:: https://img.shields.io/badge/recipe-pymt_era5-green.svg -->
        :target: https://anaconda.org/conda-forge/pymt_era5 -->

.. image:: https://readthedocs.org/projects/pymt-era5/badge/?version=latest
        :target: https://pymt-era5.readthedocs.io/en/latest/?badge=latest
        :alt: Documentation Status

.. image:: https://img.shields.io/badge/License-MIT-blue.svg
        :target: hhttps://github.com/gantian127/pymt_era5/blob/master/LICENSE

.. .. image:: https://github.com/gantian127/pymt_era5/actions/workflows/test.yml/badge.svg
        :target: https://github.com/gantian127/pymt_era5/actions/workflows/test.yml

.. .. image:: https://github.com/gantian127/pymt_era5/actions/workflows/flake8.yml/badge.svg
        :target: https://github.com/gantian127/pymt_era5/actions/workflows/flake8.yml

.. .. image:: https://github.com/gantian127/pymt_era5/actions/workflows/black.yml/badge.svg
        :target: https://github.com/gantian127/pymt_era5/actions/workflows/black.yml


pymt_era5 is a package that converts `bmi_era5 package <https://github.com/gantian127/bmi_era5>`_ into a reusable,
plug-and-play data component for `PyMT <https://pymt.readthedocs.io/en/latest/?badge=latest>`_ modeling framework
developed by Community Surface Dynamics Modeling System (`CSDMS <https://csdms.colorado.edu/wiki/Main_Page>`_).
This allows `ERA5 datasets <https://confluence.ecmwf.int/display/CKB/ERA5>`_ (currently support 3 dimensional data) to be easily coupled with other datasets or models that expose
a `Basic Model Interface <https://bmi.readthedocs.io/en/latest/>`_.

---------------
Installing pymt
---------------

Installing `pymt` from the `conda-forge` channel can be achieved by adding
`conda-forge` to your channels with:

.. code::

  conda config --add channels conda-forge

*Note*: Before installing `pymt`, you may want to create a separate environment
into which to install it. This can be done with,

.. code::

  conda create -n pymt python=3
  conda activate pymt

Once the `conda-forge` channel has been enabled, `pymt` can be installed with:

.. code::

  conda install pymt

It is possible to list all of the versions of `pymt` available on your platform with:

.. code::

  conda search pymt --channel conda-forge

--------------------
Installing pymt_era5
--------------------

To install `pymt_era5`, use pip

.. code::

  pip install pymt_era5

or conda

.. code::

  conda install -c conda-forge pymt_era5

--------------
Citation
--------------
Please include the following references when citing this software package:

Gan, T., Tucker, G.E., Hutton, E.W.H., Piper, M.D., Overeem, I., Kettner, A.J.,
Campforts, B., Moriarty, J.M., Undzis, B., Pierce, E., McCready, L., 2024:
CSDMS Data Components: data–model integration tools for Earth surface processes
modeling. Geosci. Model Dev., 17, 2165–2185. https://doi.org/10.5194/gmd-17-2165-2024

Gan, T. (2025). PyMT plugin for CSDMS ERA5 Data Component. Zenodo.
https://zenodo.org/doi/10.5281/zenodo.10368880

--------------
Coding Example
--------------
You can learn more details about the coding example from the
`tutorial notebook <https://github.com/gantian127/pymt_era5/blob/master/notebooks/pymt_era5.ipynb>`_.
