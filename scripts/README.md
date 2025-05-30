# Utility Scripts

This directory contains utility scripts for data processing, model training, and automation tasks.

## Available Scripts

- `data_download.py` - Download and update price data
- `preprocess.py` - Data preprocessing pipeline
- `train_model.py` - Model training script
- `evaluate_model.py` - Model evaluation script

## Usage

Scripts can be run from the project root directory:

```bash
python scripts/data_download.py
python scripts/preprocess.py
python scripts/train_model.py
python scripts/evaluate_model.py
```

## Adding New Scripts

1. Follow the naming convention
2. Add proper documentation and argparse
3. Include error handling
4. Add unit tests in the `tests/` directory
