# da5-notebooks

This repository contains Jupyter notebooks for the JWST DA build 5.

## Contents

This repository holds the notebooks themselves, but in an unexecuted form. If you want to view the notebooks, you can either execute them individually, or build the web page preview of them.

### Running Notebooks Interactively

All the notebooks can be executed if you have the correct dependencies installed.  See the `requirements.txt` file next to each notebook to see its requirements. (In most cases these should be installable via conda.)

### Building Locally

Alternatively, if you would like to execute the notebooks and view rendered HTML versions locally, you can clone this repo and do ``python convert.py``. This requires the [nbpages](https://github.com/eteq/nbpages) python package, which you can most easily install by doing ``pip install -e git+https://github.com/eteq/nbpages.git#egg=nbpages``.


