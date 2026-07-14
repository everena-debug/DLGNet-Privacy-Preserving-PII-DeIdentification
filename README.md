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

The notebook includes

- preprocessing pipeline
- random seed initialization
- hyperparameter configuration
- prompt template
- evaluation pipeline
- automatic generation of manuscript tables

## Citation

If you use this repository, please cite the corresponding publication after publication.
