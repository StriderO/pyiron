# pyiron_docs

This repository contains the rst documentation files for the pyiron package. The documentation is built with the 
[sphinx document generator](http://www.sphinx-doc.org/en/stable/index.html). The [matplotlib](https://matplotlib.org/) 
developers have developed a nice [introductory documentation](https://matplotlib.org/) on using sphinx which includes a 
[cheat-sheat](https://matplotlib.org/sampledoc/cheatsheet.html) which you could find useful.

## Dependencies

sphinx can be installed using conda::


`conda install sphinx`

or pip

`pip install sphinx`

Additionally the nbsphinx package should also be installed (to automatically generate rst files from notebooks)::

`conda install -c conda-forge nbsphinx`

Additionally the sphinx napoleon external package should also be used http://sphinxcontrib-napoleon.readthedocs.io/en/latest/index.html


## Usage 

The documentation is automatically generated by executing make.py

`python make.py <modules source directory> <apidoc directory> <destination directory>`

## Docstring style

We try to maintain the [Google Style Python Docstrings](http://sphinxcontrib-napoleon.readthedocs.io/en/latest/example_google.html) format while entering the docstrings. 




