# DSCI-6650 Assignment 1

## Overview

The assignment solution is presented in a single, self-contained notebook, so reproducing the results is just a matter of running through the notebook. The most difficult part is likely to be ensuring the notebook is run in an environment that 1) can run Jupyter notebooks; and 2) has the required dependencies installed.

## Google Colab

Perhaps the easiest way to run the assignment-1 notebook is just to upload it to Google Colab and run in there. This way, the dependencies should all be in place (as verified on 2025-06-18). This comes with the drawback that running in the Google Colab environment is very slow, as compute resources are limited.

## Local Usage

Depending on the user's system, this is probably the faster way to run through the simulations in the notebook. However, this assumes that the user either has the necessary dependencies installed, or is comfortable enough with Python and poetry to install a virtualenv with the required dependencies.

That being said, the only third-party packages required are NumPy, matplotlib, and SciPy, which are fairly standard.

### Prerequisites

- Python 3.13
- [Poetry](https://python-poetry.org/)

### Installation using Poetry

- Navigate to the project directory and run the following command:

```
poetry install --no-root
```
