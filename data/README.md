# Dataset Information

This directory contains the processed datasets used in the experimental workflow.

## Included Datasets

1. German Credit dataset
2. Australian Credit Approval dataset
3. Default of Credit Card Clients (Taiwan) dataset

The files under `processed/` are the cleaned versions used by the experimental notebooks.

## Processing

The complete auditing and preprocessing procedures are documented in:

- `01_Dataset_Audit.ipynb`
- `02_Preprocessing_Protocol.ipynb`

The preprocessing protocol includes dataset validation, missing-value handling, categorical encoding, numerical transformation, feature mapping, and leakage checks.

## Target Variables

The target variables were standardized for binary credit-risk classification. Dataset-specific mappings and class distributions are reported in the dataset-audit outputs.

## Important Data-Use Note

The datasets remain subject to the terms and attribution requirements of their original providers. Inclusion in this repository is solely for reproducibility of the associated academic research.
