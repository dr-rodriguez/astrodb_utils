# astrodb_utils
[![build](https://github.com/astrodbtoolkit/astrodb-scripts/actions/workflows/run_tests.yml/badge.svg)](https://github.com/astrodbtoolkit/astrodb-scripts/actions/workflows/run_tests.yml)
[![Documentation Status](https://readthedocs.org/projects/astrodb-utils/badge/?version=latest)](https://astrodb-utils.readthedocs.io/en/latest/)
[![PyPI - Version](https://img.shields.io/pypi/v/astrodb-utils)](https://pypi.org/project/astrodb-utils/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.14397585.svg)](https://doi.org/10.5281/zenodo.14397585)


The AstroDB Toolkit provides a set of tools to help astronomers work with and create databases. 
The `astrodb_utils` package provides a set of functions to query and ingest data into databases built with the `astrodb-template-db` schema.

[Documentation for the Toolkit](https://astrodb-utils.readthedocs.io/en/stable/)

---

Manual build of the documentation:
```bash
pip install -e ".[docs]"
sphinx-autobuild docs docs/_build/html
```

If you get an error with Pandoc, you can install it with:
```bash
conda install -c conda-forge pandoc
```
See https://pandoc.org/installing.html for other options
