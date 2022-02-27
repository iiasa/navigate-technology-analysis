# NAVIGATE - Analyses

![License](https://img.shields.io/github/license/iiasa/navigate-technology-analysis)
[![python](https://img.shields.io/badge/python-3.7_|_3.8_|_3.9-blue?logo=python&logoColor=white)](https://github.com/IAMconsortium/pyam)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

Copyright (c) 2022 IIASA; this repository is released under the [MIT License](LICENSE). 

## Overview

<img src="./_static/NAVIGATE-logo.png" align="right" alt="Horizon 2020 NAVIGATE" />

In the NAVIGATE project (Work Package 2), we compared IAMs based on observed
characteristics of model results that are closely linked to the specification of
technologies in the models, even if details of the implementation in the models differ.

In particular, we looked at the growth rate of various energy sector technologies and
the implied learning rates, where investment costs for technologies become cheaper as
cumulative installed capacity increases.
The aim was to identify the ranges of these parameters across models, distinguishing
between granular and “lumpy” technologies (i.e., technologies with few but large units,
e.g., nuclear power plants).

This repository contains a notebook to easily create plots to compare indicators
across models, regions or technologies.

## The pyam package

<img src="https://github.com/IAMconsortium/pyam/raw/main/doc/logos/pyam-logo.png" width="133" height="100" align="right" alt="pyam logo" />

The notebook uses the Python package **pyam**, an open-source community toolbox for
analysis & visualization of scenario data.
The package was developed to facilitate working with timeseries scenario data
conforming to the format developed by the
[Integrated Assessment Modeling Consortium (IAMC)](https://www.iamconsortium.org).
The package is used in ongoing assessments by the IPCC and in many model comparison
projects at the global and national level, including several Horizon 2020 projects.

[Read the docs](https://pyam-iamc.readthedocs.io) for more information!

## Getting started

To run the notebooks on your machine, please install Python version 3.7 or higher.
To install the required packages and dependencies, download or git-clone this repository
and run the following command in the root folder:

```
pip install -r requirements.txt
```

Then, you can start a Jupyter notebook using

```
jupyter notebook
```

## Funding acknowledgement

<img src="./_static/EU-logo-300x201.jpg" width="80" height="54" align="left" alt="EU logo" />
This project has received funding from the European Union’s Horizon 2020 research
and innovation programme under grant agreement No. 821124 (NAVIGATE).