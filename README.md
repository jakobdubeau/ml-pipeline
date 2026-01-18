## End-to-End Machine Learning Pipeline for Health Outcome Prediction

This repository implements an end-to-end machine learning workflow for predicting health outcomes using synthetic data. It covers data preparation, classical machine learning models, and neural networks, focusing on sound evaluation, reproducibility, and model comparison across approaches.

### Contents

**`notebooks/01-data-audit.ipynb`**

- Cleans and standardizes raw data
- Handles missing values and categorical normalization
- Removes non-informative and redundant features
- Analyzes feature distributions and class balance
- Outputs a modeling-ready dataset

**`notebooks/02-classical-models.ipynb`**

- Builds leakage-aware preprocessing pipelines
- Trains and tunes classic machine learning models
- Evaluates models using cross-validation
- Compares performance and generalization

**`notebooks/03-neural-network.ipynb`**

- Trains feed-forward neural networks
- Analyzes overfitting and learning dynamics
- Applies early stopping and regularization
- Explores architectural trade-offs
- Compares neural networks against classical models.

### How to run
1. Open the notebooks in Jupyter/VS Code.
2. Run cells top-to-bottom.

### Notes
This work was originally developed in an academic setting and later refactored for portfolio use.
