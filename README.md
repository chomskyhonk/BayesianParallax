# BayesianParallax

A study on Bayesian stellar distance estimation using Gaia DR2 parallax measurements. This project explores progressively more informative Bayesian posteriors, starting from parallax-only inference and extending to a full model incorporating photometry, colour, and extinction.

## Overview

This repository contains research on applying Bayesian inference methods to estimate stellar distances from Gaia DR2 parallax measurements. The work demonstrates how incorporating additional observational data (photometry, colour indices, and extinction estimates) leads to more accurate distance posteriors compared to naive parallax inversion.

## Project Structure

```
BayesianParallax/
├── README.md              # This file
├── requirements.txt       # Python dependencies
├── .gitignore            # Git ignore patterns
│
├── notebooks/            # Jupyter notebooks with analysis
│   └── README.md        # Notebook documentation
│
├── src/                  # Reusable Python modules
│   └── README.md        # Source code documentation
│
├── data/                 # Data directory (gitignored)
│   ├── raw/             # Original data files
│   ├── processed/       # Processed data
│   └── README.md        # Data documentation
│
├── results/              # Analysis outputs
│   ├── figures/         # Generated plots
│   ├── tables/          # Result tables
│   └── README.md        # Results documentation
│
├── docs/                 # Documentation and thesis
│   └── README.md        # Documentation index
│
└── tests/                # Unit tests (optional)
```

## Getting Started

### Prerequisites

- Python 3.8 or higher
- Jupyter Notebook or JupyterLab
- Git

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/chomskyhonk/BayesianParallax.git
   cd BayesianParallax
   ```

2. Create a virtual environment (recommended):
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

### Usage

1. Start Jupyter:
   ```bash
   jupyter notebook
   ```

2. Navigate to the `notebooks/` directory and open the analysis notebooks

3. Follow the notebooks in order to reproduce the analysis

## Methodology

The project implements three progressively more sophisticated Bayesian models:

1. **Parallax-Only Model**: Basic Bayesian inference using only parallax measurements
2. **Photometry Model**: Incorporates apparent magnitude and colour information
3. **Full Model**: Complete model including photometry, colour, and extinction corrections

Each model produces posterior distributions for stellar distances, which are compared to assess the information gain from additional observational constraints.

## Data

This project uses data from:
- **Gaia DR2**: Parallax measurements and astrometric data
- **Photometric catalogs**: For colour indices and apparent magnitudes
- **Extinction maps**: For interstellar extinction corrections

*Note: Data files are not included in the repository due to size. See `data/README.md` for instructions on obtaining the data.*

## Results

Analysis results including figures and tables are stored in the `results/` directory. Key findings include:
- Comparison of distance posteriors across different models
- Quantification of information gain from additional observables
- Validation against known stellar distances

## Documentation

Complete documentation including the full thesis can be found in the `docs/` directory.

## Dependencies

Key dependencies include:
- NumPy, SciPy, Pandas - Scientific computing
- PyMC3, ArviZ - Bayesian inference
- Matplotlib, Seaborn - Visualization
- Astropy, Astroquery - Astronomy tools

See `requirements.txt` for the complete list.

## Contributing

This is a research project. If you find issues or have suggestions, please open an issue or submit a pull request.

## License

Please refer to the LICENSE file for licensing information.

## Citation

If you use this work in your research, please cite:

```
[Citation information will be added after publication]
```

## Acknowledgments

- European Space Agency (ESA) for the Gaia mission data
- Gaia Data Processing and Analysis Consortium (DPAC)
- [Add any other acknowledgments]

## Contact

For questions or collaboration inquiries, please open an issue on GitHub.

---

**Repository Status**: Active Development

Last Updated: February 2026
