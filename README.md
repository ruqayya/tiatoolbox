<p align="center">
  <img src="https://raw.githubusercontent.com/TissueImageAnalytics/tiatoolbox/develop/docs/tiatoolbox-logo.png">
</p>
<h1 align="center">TIA Toolbox</h1>
<p align="center">
  <a href="https://tia-toolbox.readthedocs.io/en/latest/?badge=latest">
    <img src="https://readthedocs.org/projects/tia-toolbox/badge/?version=latest" alt="Documentation Status" />
  </a>
  <a href="https://travis-ci.com/github/TissueImageAnalytics/tiatoolbox">
    <img src="https://app.travis-ci.com/TissueImageAnalytics/tiatoolbox.svg?branch=master" alt="Travis CI Status" />
  </a>
    <a href="https://codecov.io/gh/TissueImageAnalytics/tiatoolbox">
      <img src="https://codecov.io/gh/TissueImageAnalytics/tiatoolbox/branch/master/graph/badge.svg?token=7UZEMacQHm"/>
    </a>
    <a href="https://github.com/psf/black">
      <img src="https://img.shields.io/badge/code%20style-black-000000.svg"/>
    </a>
    <a href="https://github.com/TissueImageAnalytics/tiatoolbox/tree/master#license">
      <img src="https://img.shields.io/badge/license-BSD--3--clause-orange" />
    </a>
  <br>
    <br>
  <a href="https://badge.fury.io/py/tiatoolbox">
    <img src="https://badge.fury.io/py/tiatoolbox.svg" alt="PyPI Status" />
  </a>
    <a href="https://pepy.tech/project/tiatoolbox">
      <img src="https://static.pepy.tech/personalized-badge/tiatoolbox?period=total&units=international_system&left_color=grey&right_color=green&left_text=Downloads"/>
    </a>
    <br>
    <a href="https://anaconda.org/conda-forge/tiatoolbox">
      <img src="https://img.shields.io/conda/vn/conda-forge/tiatoolbox" />
    </a>
    <a href="https://anaconda.org/conda-forge/tiatoolbox">
        <img src="https://anaconda.org/conda-forge/tiatoolbox/badges/downloads.svg" />
    </a>

  <br>
    <br>
  <a href="https://doi.org/10.1101/2021.12.23.474029"><img src="https://img.shields.io/badge/bioRxiv-10.1101%2F2021.12.23.474029-blue" alt="DOI"></a>
  <a href="https://zenodo.org/badge/latestdoi/267705904"><img src="https://zenodo.org/badge/267705904.svg" alt="DOI"></a>
</p>

Computational Pathology Toolbox developed at the TIA Centre

## Getting Started

### All Users

This package is for those interested in digital pathology: including graduate students, medical staff, members of the TIA Centre and of PathLAKE, and anyone, anywhere, who may find it useful. We will continue to improve this package, taking account of developments in pathology, microscopy, computing and related disciplines. Please send comments and criticisms to **[tia@dcs.warwick.ac.uk](mailto:tialab@dcs.warwick.ac.uk)**.

**`tiatoolbox`** is a multipurpose name that we use for 1) a certain computer program, 2) a Python package of related programs, created by us at the TIA Centre to help people get started in Digital Pathology, 3) this repository, 4) a certain virtual environment.


### Developers

Anyone wanting to contribute to this repository, please first look at our [Wiki](https://github.com/TissueImageAnalytics/tiatoolbox/wiki) and at our web page for [contributors](https://github.com/TissueImageAnalytics/tiatoolbox/blob/master/CONTRIBUTING.rst). See also the *Prepare for development* section of this document.

### Links, if needed
The [bash](https://www.gnu.org/software/bash) shell is available on all commonly encountered platforms. Commands in this README are in bash. Windows users can use the command prompt to install conda and python packages.

[conda](https://github.com/conda/conda) is a management system for software packages and [virtual environments](https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/environments.html). To get `conda`, download [Anaconda](https://www.anaconda.com/), which includes hundreds of the most useful Python packages, using 2GB disk space. Alternatively, [miniconda](https://docs.conda.io/en/latest/miniconda.html) uses 400MB, and packages can be added as needed.

[Github](https://github.com/about) is powered by the version control system [git](https://git-scm.com/), which has many users and uses. In Github, it is used to track versions of code and other documents.


### Examples Taster

1. [Click here](https://github.com/TissueImageAnalytics/tiatoolbox/tree/develop/examples) for [jupyter notebooks](https://jupyter.org/), hosted on the web, with demos of `tiatoolbox`. All necessary resources to run the notebooks are remotely provided, so you don't need to have Python installed on your computer.
2. Click on a filename with suffix `.ipynb` and the notebook will open in your browser.
3. Click on one of the two blue checkboxes in your browser window labelled either **Open in Colab** or **Open in Kaggle**: [colab](https://colab.research.google.com/notebooks/intro.ipynb#) and [kaggle](https://www.kaggle.com/) are websites providing free-of-charge platforms for running jupyter notebooks.
4. Operate the notebook in your browser, editing, inserting or deleting cells as desired.
5. Changes you make to the notebook will last no longer than your colab or kaggle session.

### Install Python package

If you wish to use our programs, perhaps without developing them further, run the command `pip install tiatoolbox` or `pip install --ignore-installed --upgrade tiatoolbox` to upgrade from an existing installation.
Detailed installation instructions can be found in the [documentation](https://tia-toolbox.readthedocs.io/en/latest/installation.html).

To understand better how the programs work, study the jupyter notebooks referred to under the heading **Examples Taster**.

### Command Line
tiatoolbox supports various features through command line. For more information, please try `tiatoolbox --help`

### Prepare for development

Prepare a computer as a convenient platform for further development of the Python package `tiatoolbox` and related programs as follows.
1. Install [pre-requisite software](https://tia-toolbox.readthedocs.io/en/latest/installation.html)
2. Open a terminal window<br/>

```sh
    $ cd <future-home-of-tiatoolbox-directory>
```

3. Download a complete copy of the `tiatoolbox`.

```sh
    $ git clone https://github.com/TissueImageAnalytics/tiatoolbox.git
```

4. Change directory to `tiatoolbox`

```sh
    $ cd tiatoolbox
```

5. Create virtual environment for TIAToolbox using

```sh
    $ conda env create -f requirements.dev.conda.yml # for linux/mac only.
    $ conda activate tiatoolbox-dev
```
or

```sh
    $ conda create -n tiatoolbox-dev python=3.8 # select version of your choice
    $ conda activate tiatoolbox-dev
    $ pip install -r requirements_dev.txt
```
6. To use the packages installed in the environment, run the command:

```sh
    $ conda activate tiatoolbox-dev
```


### License

The source code TIA Toolbox (tiatoolbox) as hosted on GitHub is released under the [The 3-Clause BSD License].

The full text of the licence is included in [LICENSE](https://raw.githubusercontent.com/TissueImageAnalytics/tiatoolbox/develop/LICENSE).

[The 3-Clause BSD License]: https://opensource.org/licenses/BSD-3-Clause

### Auxiliary Files

Auxiliary files, such as pre-trained model weights downloaded from the TIA Centre webpage (https://warwick.ac.uk/tia/), are provided under the [Creative Commons Attribution-NonCommercial-ShareAlike Version 4 (CC BY-NC-SA 4.0) license](https://creativecommons.org/licenses/by-nc-sa/4.0/).

### Dual License

If you would like to use any of the source code or auxiliary files (e.g. pre-trained model weights) under a different license agreement please contact the Tissue Image Analytics (TIA) Centre at the University of Warwick (tia@dcs.warwick.ac.uk).
