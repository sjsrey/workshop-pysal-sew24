## Installation

We will be using a number of Python packages for geospatial analysis.

We recommend using the [conda](https://conda.io/en/latest) package manager, which can be obtained by
installing the [Anaconda Distribution](https://www.anaconda.com/download-old) (a free Python distribution for data
science), or through [miniconda](docs.anaconda.com/free/miniconda) (a minimal distribution containing only
Python and the conda package manager). 


Once you have conda installed, you can create the environment for the workshop
using the following command issued from the top level of the repository you
cloned or the download archive:

```
conda env create -f environment.yml
```

Once this is built,  you can activate the environment with:

```
conda activate workshop-pysal
```

You can start jupyter lab with:

```
jupyter lab
```
and from there, you can open the notebooks for the workshop.

