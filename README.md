ocetrac
==============================
[![Build Status](https://github.com/ocetrac/ocetrac/workflows/Tests/badge.svg)](https://github.com/ocetrac/ocetrac/actions)
[![codecov](https://codecov.io/gh/ocetrac/ocetrac/branch/main/graph/badge.svg)](https://codecov.io/gh/ocetrac/ocetrac)
[![Conda Version](https://img.shields.io/conda/vn/conda-forge/ocetrac.svg)](https://anaconda.org/conda-forge/ocetrac)
[![pypi](https://img.shields.io/pypi/v/ocetrac.svg)](https://pypi.org/project/ocetrac)
[![downloads](https://pepy.tech/badge/ocetrac)](https://pepy.tech/project/ocetrac)
[![Documentation Status](https://readthedocs.org/projects/ocetrac/badge/?version=latest)](https://ocetrac.readthedocs.io/en/latest/?badge=latest)
[![License:MIT](https://img.shields.io/badge/License-MIT-lightgray.svg?style=flt-square)](https://opensource.org/licenses/MIT)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5102928.svg)](https://doi.org/10.5281/zenodo.5102928)
[![All platform](https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/ocetrac-feedstock?branchName=master)](https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=13414&branchName=maste)


Ocetrac is a Python 3.6+ packaged designed to label and track unique geospatial features from gridded datasets. The package is designed to accept data that have already been preprocessed, meaning that the data only contain values the user is interested in tracking. Ocetrac operates lazily with Dask so that it is memory uninhibited and fast through parallelized execution. We provide examples and demonstrate best practices as developed by the [Climate Data Science Lab](https://ocean-transport.github.io/cds_lab.html) at Columbia University / Lamont-Doherty Earth Observatory.

When using this package, please cite the original [software](https://doi.org/10.5281/zenodo.5102928). This package is also described in [Spatiotemporal Evolution of Marine Heatwaves Globally](https://journals.ametsoc.org/view/journals/atot/aop/JTECH-D-23-0126.1/JTECH-D-23-0126.1.xml). 


Installation
------------

**Conda**

To install the core package from conda-forge run: ``conda install -c conda-forge ocetrac``

**PyPI**

To install the core package run: ``pip install ocetrac``.

**GitHub**

1. Clone ocetrac to your local machine: ``git clone https://github.com/ocetrac/ocetrac.git``
2. Change to the parent directory of ocetrac
3. Install ocetrac with ``pip install -e ./ocetrac``. This will allow
   changes you make locally, to be reflected when you import the package in Python.
   
How you can contribute
----------------------

- You can get involved by trying ocetrac, filing [issues](https://github.com/ocetrac/ocetrac/issues) if you find problems, and making [pull requests](https://github.com/ocetrac/ocetrac/pulls) if you make improvements.

Acknowledgements
----------------
- We rely heavily on [scikit-image](https://peerj.com/articles/453/) and its community of contributors. 
- This work grew from a collabortion with NCAR during the ASP Graduate Visitor Program attended by Hillary Scannell. This project recieved continued support from the Leonardo DiCaprio Foundation, Microsoft, and the Gordon and Betty Moore Foundation. 
