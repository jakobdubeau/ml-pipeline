# End-to-End Machine Learning Pipeline for Health Outcome Prediction

This repository demonstrates a complete machine learning workflow for predicting health outcomes from structured tabular data. The project progresses from data preparation to classical machine learning models, and finally to deep learning, with an emphasis on generalization and regularization techniques.

## Contents

### `notebooks/01-data-audit.ipynb`

- Cleans and standardizes raw data
- Handles missing values and categorical normalization
- Removes non-informative and redundant features
- Analyzes feature distributions and class balance
- Produces a modeling-ready dataset

### `notebooks/02-classical-models.ipynb`

- Builds leakage-aware preprocessing pipelines
- Trains and tunes multiple classifiers
- Evaluates models using cross-validation
- Compares performance and generalization

### `notebooks/03-neural-network.ipynb`

- Trains feed-forward neural networks
- Analyzes overfitting and learning dynamics
- Applies early stopping and regularization
- Explores network architecture choices
- Compares neural networks with classical models.

## How to run
1. Open the notebooks in Jupyter/VS Code.
2. Run cells top-to-bottom.

## Notes
This work was originally developed in an academic setting and later refactored for portfolio use.
