<p align="center">
    <a href="http://poliastro.github.io/"><image src="http://poliastro.github.io/images/logo_text.png" alt="poliastro logo" width="675px"></a>
</p>

Name:         | poliastro
:------------:|:--------------
**Website**:  | <https://poliastro.github.io/>
**Author**:   | Juan Luis Cano Rodríguez [![orcid](https://img.shields.io/badge/id-0000--0002--2187--161X-a6ce39.svg)](http://orcid.org/0000-0002-2187-161X)
**Version**:  | 0.15.dev0

[![azure_pipelines](https://dev.azure.com/poliastro/poliastro/_apis/build/status/poliastro.poliastro?branchName=master)](https://dev.azure.com/poliastro/poliastro/_build/latest?definitionId=1&branchName=master)
[![codecov](https://img.shields.io/codecov/c/github/poliastro/poliastro.svg?style=flat-square)](https://codecov.io/github/poliastro/poliastro?branch=master)
[![codeclimate](https://api.codeclimate.com/v1/badges/fd2aa5bf8c4b7984d11b/maintainability)](https://codeclimate.com/github/poliastro/poliastro/maintainability)

[![docs](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat-square)](https://docs.poliastro.space/en/latest/?badge=latest)
[![license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/poliastro/poliastro/raw/master/COPYING)
[![doi](https://zenodo.org/badge/11178845.svg?style=flat-square)](https://zenodo.org/badge/latestdoi/11178845)
[![astropy](http://img.shields.io/badge/powered%20by-AstroPy-orange.svg?style=flat-square)](http://www.astropy.org/)
[![mailing](https://img.shields.io/badge/mailing%20list-groups.io-8cbcd1.svg?style=flat-square)](https://groups.io/g/poliastro-dev)
[![Join the chat at http://chat.poliastro.space/](https://img.shields.io/matrix/poliastro:matrix.org.svg?style=flat-square)](http://chat.poliastro.space/)

poliastro is an open source pure Python package dedicated to problems
arising in Astrodynamics and Orbital Mechanics, such as orbit
propagation, solution of the Lambert\'s problem, conversion between
position and velocity vectors and classical orbital elements and orbit
plotting, focusing on interplanetary applications. It is released under
the MIT license.

```python
from poliastro.examples import molniya

molniya.plot()
```
<p align="center">
    <image src="https://github.com/poliastro/poliastro/raw/main/docs/source/examples/molniya.png">
</p>

# Documentation

[![docs](https://img.shields.io/badge/docs-latest-brightgreen.svg?style=flat-square)](https://docs.poliastro.space/en/latest/?badge=latest)

Complete documentation, including a user guide and an API reference, can
be read on the wonderful [Read the Docs](https://readthedocs.org/).

<https://docs.poliastro.space/>

# Examples

[![mybinder](https://img.shields.io/badge/launch-binder-e66581.svg?style=flat-square)](https://beta.mybinder.org/v2/gh/poliastro/poliastro/master?filepath=index.ipynb)

In the examples directory you can find several Jupyter notebooks with
specific applications of poliastro. You can launch a cloud Jupyter
server using [binder](https://beta.mybinder.org/) to edit the notebooks
without installing anything. Try it out!

<https://beta.mybinder.org/v2/gh/poliastro/poliastro/master?filepath=index.ipynb>

# Requirements

poliastro requires the following Python packages:

- NumPy, for basic numerical routines
- Astropy, for physical units and time handling
- numba (optional), for accelerating the code
- jplephem, for the planetary ephemerides using SPICE kernels
- matplotlib, for orbit plotting
- plotly, for 2D and 3D interactive orbit plotting
- SciPy, for root finding and numerical propagation

poliastro is tested on Linux, OS X and Windows on Python 3.7 and 3.8
against latest NumPy.

[![azure_pipelines](https://dev.azure.com/poliastro/poliastro/_apis/build/status/poliastro.poliastro?branchName=master)](https://dev.azure.com/poliastro/poliastro/_build/latest?definitionId=1&branchName=master)

# Installation

The easiest and fastest way to get the package up and running is to
install poliastro using [conda](http://conda.io):

```bash
    $ conda install poliastro --channel conda-forge
```
Please check out the [documentation for alternative installation
methods](https://docs.poliastro.space/en/latest/getting_started.html#alternative-installation-methods).

# Problems and suggestions

If for any reason you get an unexpected error message or an incorrect
result, or you want to let the developers know about your use case,
please open a new issue in the [issue
tracker](https://github.com/poliastro/poliastro/issues) and we will try
to answer promptly.

# Contributing

poliastro is a community project, hence all contributions are more than
welcome! For more information, head to
[CONTRIBUTING.md](https://github.com/poliastro/poliastro/blob/master/CONTRIBUTING.md).

# Support

[![mailing](https://img.shields.io/badge/mailing%20list-groups.io-8cbcd1.svg?style=flat-square)](https://groups.io/g/poliastro-dev)
[![Join the chat at http://chat.poliastro.space/](https://img.shields.io/matrix/poliastro:matrix.org.svg?style=flat-square)](http://chat.poliastro.space/)

Release announcements and general discussion take place on our [Mailing
List](https://groups.io/g/poliastro-dev) .

For further clarifications and discussions, feel free to join Poliastro
[Chat Room](http://chat.poliastro.space/).

# Citing

If you use poliastro on your project, please [drop me a
line](mailto:hello@juanlu.space).

You can also use the DOI to cite it in your publications. This is the
latest one:

[![doi](https://zenodo.org/badge/11178845.svg?style=flat-square)](https://zenodo.org/badge/latestdoi/11178845)

And this is an example citation format:

    Juan Luis Cano Rodríguez et al.. (2015). poliastro: poliastro 0.4.0. Zenodo. 10.5281/zenodo.17462

# License

[![license](https://img.shields.io/badge/license-MIT-blue.svg?style=flat-square)](https://github.com/poliastro/poliastro/raw/master/COPYING)

poliastro is released under the MIT license, hence allowing commercial
use of the library. Please refer to the COPYING file.

# FAQ

## What\'s up with the name?

poliastro comes from Polimi, which is the shortened name of the
Politecnico di Milano, the Italian university where I was studying while
writing this software. It\'s my tiny tribute to a place I came to love.
*Grazie mille!*

## Can I do \<insert awesome thing\> with poliastro?

poliastro is focused on interplanetary applications. This has two
consequences:

- It tries to be more general than other Flight Dynamics core
  libraries more focused on Earth satellites (see [Related
  software](https://docs.poliastro.space/en/latest/about.html#related-software)
  for a brief list), allowing the algorithms to work also for orbits
  around non-Earth bodies.
- It leaves out certain features that would be too Earth-specific,
  such as TLE reading, SGP4 propagation, groundtrack plotting and
  others.

## What\'s the future of the project?

poliastro is actively maintained and receiving an influx of new
contributors thanks to the generous sponsorship of Google and the
European Space Agency. The best way to get an idea of the roadmap is to
see the [Milestones](https://github.com/poliastro/poliastro/milestones)
of the project.
