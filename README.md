# Notebooks-dev

This repository contains in-development Jupyter notebooks related to the work that we do at STScI. These notebooks may be very rough, or more for internal consumption, but at least some are likely to be "ugraded" to the [primary STScI notebooks repo](https://github.com/spacetelescope/notebooks).

These notebooks are also continuous integration to ensure that that at least they execute and can be rendered well in the browser.

## Contents

This repository holds the notebooks themselves, but in a harder-to-read unexecuted form. If you want to view the notebooks online, you should view [the rendered version](https://spacetelescope.github.io/notebooks-dev).

### Building Locally

Alternatively, if you would like to execute the notebooks and view them locally, you can clone this repo and do ``python convert.py``. This requires the [nbpages](https://github.com/eteq/nbpages) python package, which you can most easily install by doing ``pip install -e git+https://github.com/eteq/nbpages.git#egg=nbpages``.

## Contributing

If you want to suggest changes to this content (or new content!), check out the [contributing guide](CONTRIBUTING.md).

