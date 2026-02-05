# Results

This directory contains analysis results, figures, and tables.

## Structure

- `figures/` - Generated plots and visualizations
- `tables/` - Output tables and numerical results

## Usage

Save figures from notebooks:
```python
import matplotlib.pyplot as plt

# Create your plot
plt.figure()
# ... plotting code ...

# Save to results directory
plt.savefig('../results/figures/my_figure.png', dpi=300, bbox_inches='tight')
```

## Best Practices

- Use descriptive filenames (e.g., `parallax_posterior_comparison.png`)
- Save in high resolution (300 dpi) for publication quality
- Consider saving both PNG (for viewing) and PDF (for publications)
- Document what each figure shows in your notebooks
