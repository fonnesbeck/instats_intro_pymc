# Introduction to Bayesian Statistics in Python

Bayesian statistical methods offer a powerful set of tools to tackle a wide variety of data science problems. In addition, the Bayesian approach generates results that are easy to interpret and automatically account for uncertainty in quantities that we wish to estimate or predict. Historically, computational challenges have been a barrier, particularly to new users, but there now exists a mature set of probabilistic programming tools that are both capable and easy to learn. We will use the newest release of PyMC (version 5.22 or later), but the concepts and approaches that will be taught are portable to any probabilistic programming framework.

This course is intended for practicing and aspiring data scientists and analysts looking to learn how to apply Bayesian statistics and probabilistic programming to their work. It will provide learners with a high-level understanding of Bayesian statistical methods and their potential for use in a variety of applications. They will also gain hands-on experience with applying these methods using PyMC, specifically including the specification, fitting and checking of models applied to a couple of real-world datasets.

This is an introductory course, therefore no direct experience with PyMC or Bayesian statistics will be expected. However, to benefit maximally from the course, learners should have some familiarity with basic statistical modeling (things like regression and estimation) and with core components of the scientific Python stack (e.g. NumPy, pandas and Jupyter).

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

### Session 1: Introduction to Bayesian Computing
- Basic Bayes concepts and probability models
- Posterior distribution calculation
- Prior specification
- Bayesian updating
- Conjugate priors

### Session 2: Building Models with PyMC
- Building models in PyMC
- Model specification and structure
- Likelihood functions
- Prior distributions
- Model components and variables

## Day 2

### Session 3: Markov Chain Monte Carlo
- Numerical integration
- Monte Carlo integration
- Rejection sampling
- MCMC methods
- Sampling algorithms

### Session 4: Model Checking and Evaluation
- MCMC output processing
- Model checking with ArviZ
- Posterior analysis
- Model diagnostics
- Bayesian workflow
- Model evaluation and improvement
- Predictive checks
- Model comparison

