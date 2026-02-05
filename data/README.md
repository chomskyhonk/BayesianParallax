# Data

This directory contains data files for the project.

## Structure

- `raw/` - Original, immutable data files (Gaia DR2 data, etc.)
- `processed/` - Cleaned and processed data ready for analysis

## Note

⚠️ Data files are excluded from version control via `.gitignore` to avoid repository bloat.

### Adding Data

1. Place original data files in `raw/`
2. Use notebooks or scripts to process data
3. Save processed data to `processed/`

### Gaia DR2 Data

For downloading Gaia data, use `astroquery`:
```python
from astroquery.gaia import Gaia
# Your query here
```

Refer to notebooks for specific data retrieval examples.
