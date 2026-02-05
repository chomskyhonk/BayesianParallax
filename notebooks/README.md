# Notebooks

This directory contains Jupyter notebooks for the Bayesian stellar distance estimation analysis.

## Notebooks

Place your analysis notebooks here. Suggested naming convention:
- `01_data_exploration.ipynb` - Initial data exploration and visualization
- `02_parallax_only_model.ipynb` - Bayesian inference using parallax measurements only
- `03_full_bayesian_model.ipynb` - Complete model with photometry, colour, and extinction

## Usage

To run the notebooks:

1. Ensure you have installed all dependencies from `requirements.txt`
2. Start Jupyter:
   ```bash
   jupyter notebook
   ```
3. Open the desired notebook and run the cells

## Notes

- Notebooks should be self-contained with explanations and visualizations
- Save output figures to `../results/figures/` for easy reference
- Large data files should be placed in `../data/` directory
