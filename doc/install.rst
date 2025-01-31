.. _install:

=====================================
Installation, testing and development
=====================================

Dependencies
------------

pyts requires:

- Python (>= 3.5)
- NumPy (>= 1.15.4)
- SciPy (>= 1.1.0)
- Scikit-Learn (>=0.20.1)
- Numba (>0.41.0)

To run the examples Matplotlib (>=2.0.0) is required.


User installation
-----------------

If you already have a working installation of numpy, scipy, scikit-learn and
numba, you can easily install pyts using ``pip``::

    pip install pyts

or ``conda`` via the ``conda-forge`` channel::

    conda install -c conda-forge pyts

You can also get the latest version of pyts by cloning the repository::

    git clone https://github.com/johannfaouzi/pyts.git
    cd pyts
    pip install .


Testing
-------

After installation, you can launch the test suite from outside the source
directory using pytest::

    pytest pyts


Development
-----------

The development of this package is in line with the one of the scikit-learn
community. Therefore, you can refer to their
`Development Guide <https://scikit-learn.org/stable/developers/>`_.
A slight difference is the use of Numba instead of Cython for optimization.
