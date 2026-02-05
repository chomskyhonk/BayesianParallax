# Source Code

This directory is for reusable Python modules and functions.

## Purpose

While Jupyter notebooks are great for exploratory analysis, any reusable code should be extracted into Python modules here for:
- Better code organization
- Easier testing
- Reusability across notebooks

## Suggested Modules

- `bayesian_models.py` - Bayesian model definitions
- `data_processing.py` - Data loading and preprocessing functions
- `plotting.py` - Custom plotting functions
- `utils.py` - Utility functions

## Usage

Import these modules in your notebooks:
```python
import sys
sys.path.append('../src')
from bayesian_models import parallax_posterior
```
