# Introduction to Bayesian Statistics with PyMC

This is a two-day workshop on Bayesian statistics using PyMC. Each session is 2 hours long.

## Setting up the Environment

If using Anaconda/Miniforge:
The repository contains an `environment.yml` file with all required packages. Run:

    mamba env create

if you are using Miniforge, or if you installed Anaconda, you can use:

    conda env create

from the main course directory (use `conda` instead of `mamba` if you installed Anaconda). Then activate the environment:

    mamba activate intro_pymc
    # or
    conda activate intro_pymc

If using Pixi:
The repository contains a `pixi.toml` file. From the main course directory, simply run:

    pixi install
    pixi shell

Then, you can start **JupyterLab** to access the materials:

    jupyter lab

For those who like to work in VS Code, you can also run Jupyter notebooks from within VS Code. To do this, you will need to install the [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter). Once this is installed, you can open the notebooks in the `notebooks` subdirectory and run them interactively.

## Day 1

### Introduction to Bayesian Computing

### Building Models with PyMC

## Day 2

### Markov Chain Monte Carlo

### Model Checking and Evaluation

