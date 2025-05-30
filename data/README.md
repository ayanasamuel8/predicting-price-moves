# Data Directory

This directory contains all data files for the price movement prediction project.

## Structure

```
data/
├── raw/              # Original, immutable data
├── interim/          # Intermediate data that has been transformed
├── processed/        # Final, canonical data sets for modeling
└── external/         # Data from third party sources
```

## Guidelines

1. Raw data should never be modified
2. Document data sources and collection methods
3. Include data dictionaries where applicable
4. Large data files should be added to .gitignore
5. Consider using data version control (DVC) for large datasets

## Data Files

### Raw Data

- Place original, unmodified data files here
- Document data sources and collection dates

### Interim Data

- Store intermediate processing steps
- Include preprocessing scripts in `scripts/` directory

### Processed Data

- Final datasets ready for modeling
- Include feature engineering documentation

### External Data

- Third-party data sources
- Document data sources and licenses
