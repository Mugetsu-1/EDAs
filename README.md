# Exploratory Data Analysis Collection

This repository contains multiple end-to-end EDA projects, each organized in its own folder with notebook(s) and CSV data files.

## Projects

- `EDAs/BestSellingBooksEDA`
- `EDAs/CreditCardFraudEDA`
- `EDAs/DigitalIDusagesEDA`
- `EDAs/GoldpriceEDA`
- `EDAs/myntaEDA`
- `EDAs/NvidiaEDA`
- `EDAs/WW1EDA`

## Standard EDA Coverage

Across notebooks, the analysis workflow now consistently emphasizes:

1. Data loading and schema inspection
2. Data cleaning and type correction
3. Missing-value handling and (where applicable) interpolation
4. Outlier handling
5. Univariate and multivariate analysis
6. Feature extraction and transformation
7. Encoding, scaling, and sklearn preprocessing pipelines
8. Final written summary/review markdown

## Advanced Checklist Coverage

The upgraded notebooks include explicit treatment (where dataset/task permits) of:

- Data extraction
- Data interpolation
- Handling missing data
- Handling outliers
- Encoding
- Normalization
- Standardization
- Handling imbalanced datasets
- SMOTE

## Recent Update

- Added an extra markdown section in notebooks that already had a summary/review:
  `Additional Update: What Was Added and Reviewed More`.
- Upgraded notebook structure for clearer analysis flow and stronger preprocessing documentation.

## Requirements

- Python 3.10+
- Jupyter Notebook / JupyterLab
- Packages: `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
- Optional (for imbalance sections): `imbalanced-learn`

## Installation

```bash
pip install jupyter pandas numpy matplotlib seaborn scikit-learn imbalanced-learn
```

## Running

```bash
jupyter notebook
```

Then open any notebook inside `EDAs/*`.
