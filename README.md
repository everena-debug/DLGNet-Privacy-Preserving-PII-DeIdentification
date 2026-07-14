# DLGNet: A Deep Learning and Generative Framework for Privacy-Preserving PII De-Identification with Semantic Verification

## Overview

This repository contains the implementation of DLGNet, a privacy-preserving framework for Personally Identifiable Information (PII) de-identification. The framework integrates DeBERTa-based token classification, LLM-based semantic verification, and generative surrogate replacement to detect, verify, and replace sensitive entities while preserving document utility.

## Features

- DeBERTa-v3 token-level PII detection
- TinyLlama semantic verification
- WGAN-GP-based surrogate name generation
- Type-aware replacement strategy
- Residual PII validation
- Utility preservation evaluation
- Automatic generation of experimental tables

## Repository

The notebook

```
DLGNet_Reproducibility.ipynb
```

contains the complete implementation of the proposed framework, including:

- preprocessing
- model training
- semantic verification
- surrogate generation
- evaluation
- reproducibility settings
- manuscript table generation

## Dataset

The dataset is publicly available through Kaggle.

Learning Agency Lab – PII Detection Removal from Educational Data

https://www.kaggle.com/competitions/pii-detection-removal-from-educational-data

The raw dataset is **not redistributed** in this repository due to privacy considerations.

Only public dataset links and synthetic examples are provided.

## Reproducibility

The notebook `DLGNet_Reproducibility.ipynb` contains the complete implementation of the proposed DLGNet framework, including:

- Data preprocessing and BIO label consolidation
- DeBERTa-v3 token-level PII detection
- TinyLlama semantic verification
- WGAN-GP-based surrogate generation
- Type-aware entity replacement
- Residual PII validation
- Utility preservation evaluation
- Random seed initialization and reproducibility settings
- Hyperparameter configuration
- Prompt template for semantic verification
- Evaluation pipeline
- Automatic generation of performance, ablation, comparative analysis, false-negative rate, and runtime evaluation tables

All manuscript tables are generated directly from the execution of the notebook rather than being manually entered.

The repository does not contain raw PII data. Users should download the public Kaggle dataset separately and place it in the specified input directory before running the notebook.

## Execution

1. Download the public Kaggle dataset.
2. Update the dataset path in the configuration cell if necessary.
3. Execute all notebook cells sequentially from Cell 1 to the final cell.
4. The notebook automatically trains the models, evaluates performance, and generates the manuscript tables.

## Citation

If you use this repository in your research, please cite the corresponding journal publication after publication.

The bibliographic details will be updated after the article is published.
