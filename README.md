# Bayesian Distance Estimation with Gaia DR2

This repository contains the python code in jupyternotebooks format and accompanying report for a study on
Bayesian stellar distance estimation using Gaia DR2 parallax measurements.
The work explores progressively more informative Bayesian posteriors,
starting from parallax-only inference and extending to a full model
incorporating photometry, colour, and extinction.

## Contents

- `bayesian_parallax.pdf`  
  The final written report describing the methodology, Bayesian framework,
  results, and conclusions.

- `parallaxestimates.ipynb`  
  A Jupyter notebook containing all code used for data selection, posterior
  construction, MCMC sampling, and performance evaluation.

## Methodology Overview

The analysis compares three distance estimation approaches:
1. Naïve parallax inversion
2. Bayesian inference using a parallax-only likelihood and a physically
   motivated distance prior
3. A full Bayesian posterior jointly inferring distance and absolute magnitude,
   incorporating photometric, colour, and extinction information

Distance estimates are evaluated against Gaia GSP-Phot distances using both
visual diagnostics and quantitative performance metrics.

The full Bayesian methodology and justification, as well as the physics and 
statistical analysis - including figures and tables - are all laid out in
the .pdf file. 

## Requirements

The notebook was developed using Python 3 and relies on common scientific
libraries. A minimal set of dependencies is:
numpy
scipy
matplotlib
pandas
astropy
emcee
corner

(Exact versions are not strictly required for reproducing the main results.)

## Usage

Open and run `parallaxestimates.ipynb` sequentially to reproduce the figures and
statistics presented in the report. The notebook is self-contained and
includes explanatory comments throughout.

## Implementation

All analysis code is written in Python and provided in a Jupyter notebook
(`parallaxestimates.ipynb`)

## Notes

- Gaia DR2 parallaxes include a global zero-point offset, which is explicitly
  accounted for in the likelihood.
- The colour–magnitude relation is derived empirically from the dataset and
  should not be interpreted as a universal stellar population model.

## Contact

For questions or collaboration inquiries:
- GitHub Issues: [Project Issues](https://github.com/chomskyhonk/BayesianStellarParameters/issues)
- (LinkedIn: https://www.linkedin.com/in/billy-harrison-74ab66251)



