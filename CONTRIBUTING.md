# Contributing to BayesianParallax

Thank you for your interest in contributing to this project!

## How to Add Your Files

### Adding Your Jupyter Notebook

1. Place your Jupyter notebook(s) in the `notebooks/` directory
2. Use descriptive names (e.g., `01_parallax_analysis.ipynb`, `02_full_model.ipynb`)
3. Ensure notebooks have proper markdown cells explaining the analysis
4. Clear output cells before committing (optional, but keeps repo clean)

### Adding Your Thesis PDF

1. Place your thesis PDF in the `docs/` directory
2. Name it descriptively (e.g., `thesis.pdf` or `bayesian_parallax_thesis.pdf`)

### Adding Your Requirements File

1. If you have a requirements.txt file with your specific dependencies:
   - Replace or update the existing `requirements.txt` in the root directory
   - Ensure all versions are specified for reproducibility
   - Consider using `pip freeze > requirements.txt` from your working environment

### Adding Data

1. Place raw data files in `data/raw/`
2. Place processed data in `data/processed/`
3. **Note**: Large data files are gitignored. Consider:
   - Providing download instructions in `data/README.md`
   - Using Git LFS for large files if necessary
   - Hosting data separately (Zenodo, Figshare, etc.)

## Git Workflow

1. Add your files:
   ```bash
   git add notebooks/your_notebook.ipynb
   git add docs/thesis.pdf
   git add requirements.txt
   ```

2. Commit your changes:
   ```bash
   git commit -m "Add analysis notebooks and thesis"
   ```

3. Push to GitHub:
   ```bash
   git push origin main
   ```

## Best Practices

- **Code Quality**: Ensure code is well-commented and follows PEP 8 style
- **Notebooks**: Include markdown cells explaining each analysis step
- **Data**: Document data sources and preprocessing steps
- **Reproducibility**: Make sure analysis can be reproduced by others

## Questions?

If you have questions or need help, please open an issue on GitHub.
