Orange3 RecommenderSystems
============

[![Build Status](https://travis-ci.org/biolab/orange3-text.svg?branch=master)](https://travis-ci.org/biolab/orange3-text)
[![codecov.io](http://codecov.io/github/biolab/orange3-text/coverage.svg?branch=master)](http://codecov.io/github/biolab/orange3-text?branch=master)
[![Documentation Status](https://readthedocs.org/projects/orange3-text/badge/?version=latest)](http://orange3-text.readthedocs.org/en/latest/?badge=latest)

Orange3 RecommenderSystems extends [Orange3](http://orange.biolab.si), a data mining software
package, with common functionality for make recommendations. It provides access
to publicly available data, like MovieLens, Yahoo! Music, Flixster,... Further,
it provides tools for GPU acceleration. All features can be combined with powerful data mining techniques
from the Orange data mining framework.

Installation
------------

To install the add-on with pip use

    pip install Orange3-RecommenderSystems

To install the add-on from source, run

    python setup.py install

To register this add-on with Orange, but keep the code in the development directory (do not copy it to 
Python's site-packages directory), run

    python setup.py develop

Usage
-----

After the installation, the widget from this add-on is registered with Orange. To run Orange from the terminal,
use

    python3 -m Orange.canvas

Recommender Systems widgets are in the toolbox bar under Recommender Systems section.