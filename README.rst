Installation
^^^^^^^^^^^^

Dependencies
------------

forest-gis requires:

- Python (>= 3.6)
- NumPy (>= 1.15.0)
- SciPy (>= 0.19.1)
- joblib (>= 0.14)

For Windwos
------------

If you already have a working installation of numpy and scipy,
and you plateform is Windows 32-bit or 64-bit the easiest way 
to install forest-gis is using ``pip``::

    pip install -U forest-gis

or ``conda``::

    conda install -c conda-forge forest-gis
For linux:
------------
At present, on the pypi_, we only provide wheel files supporting
Python3.6, 3.7, 3.8 for Windows 32-bit, Windows 64-bit. Though the
wheel files for linux 64-bit are also provided, you may encouter
problems if your linux system has a lower version of ``glibc`` than
ubantu 18.x because the wheel files was just compiled on ubantu 18.x
If you get wrong when use ``pip`` to install ``forest-gis``, you can
try to install forest-gis from source.

.. _pypi: https://pypi.org/project/forest-gis

For macOS:
------------
At present, build ``forest-gis`` from source as wheel files are not provied for macOS.

Build forest-gis from source
----------------------------
Before you install the ``forest-gis`` from source, you need to update
cython to the newest version. For Windows you can run ::

    pip install --verbose .

For macOS, 

.. _cython: https://cython.org/

User Guide
^^^^^^^^^^^^


