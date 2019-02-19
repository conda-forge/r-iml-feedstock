<!--
# -*- mode: jinja -*-
-->

About r-iml
===========

Home: https://github.com/christophM/iml

Package license: MIT

Feedstock license: BSD 3-Clause

Summary: Interpretability methods to analyze the behavior and predictions of any machine learning model. Implemented methods are: Feature importance described by Fisher et al. (2018) <arXiv:1801.01489>, accumulated local effects plots described by Apley (2018) <arXiv:1612.08468>, partial dependence plots described by Friedman (2001) <http://www.jstor.org/stable/2699986>, individual conditional expectation (ice) plots described by Goldstein et al. (2013) <doi:10.1080/10618600.2014.907095>, local models (variant of lime) described by Ribeiro et. al (2016) <arXiv:1602.04938>, the Shapley Value described by Strumbelj et. al (2014) <doi:10.1007/s10115-013-0679-x>,  feature interactions described by Friedman et. al <doi:10.1214/07-AOAS148> and tree surrogate models.



Current build status
====================

All platforms:
[![noarch](https://img.shields.io/circleci/project/github/conda-forge/r-iml-feedstock/master.svg?label=noarch)](https://circleci.com/gh/conda-forge/r-iml-feedstock)

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--iml-green.svg)](https://anaconda.org/conda-forge/r-iml) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-iml.svg)](https://anaconda.org/conda-forge/r-iml) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-iml.svg)](https://anaconda.org/conda-forge/r-iml) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-iml.svg)](https://anaconda.org/conda-forge/r-iml) |

Installing r-iml
================

Installing `r-iml` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
```

Once the `conda-forge` channel has been enabled, `r-iml` can be installed with:

```
conda install r-iml
```

It is possible to list all of the versions of `r-iml` available on your platform with:

```
conda search r-iml --channel conda-forge
```


About conda-forge
=================

[![Powered by NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](http://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/)
and [TravisCI](https://travis-ci.org/) it is possible to build and upload installable
packages to the [conda-forge](https://anaconda.org/conda-forge)
[Anaconda-Cloud](https://anaconda.org/) channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-iml-feedstock
========================

If you would like to improve the r-iml recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-iml-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================

* [@conda-forge/r](https://github.com/conda-forge/r/)

