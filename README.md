# End-to-End Machine Learning Pipeline for Health Outcome Prediction

This repository demonstrates a complete machine learning workflow for predicting health outcomes from structured tabular data. The project progresses from data preparation to classical machine learning models, and finally to deep learning, with an emphasis on generalization and regularization techniques.

## Contents

### `notebooks/01-data-audit.ipynb`

cleans and standardizes raw data, handles missing values and categorical normalization, removes non-informative and redundant features, analyzes feature distributions and class balance, Produces a modeling-ready dataset.

### `notebooks/02-classical-models.ipynb`

Builds leakage-aware preprocessing pipelines, trains and tunes multiple classifiers, evaluates models using cross-validation, compares performance and generalization.

### `notebooks/03-neural-network.ipynb`

Trains feed-forward neural networks, analyzes overfitting and learning dynamics, applies early stopping and regularization, explores network architecture choices, compares neural networks with classical models.

## How to run
1. Open the notebooks in Jupyter/VS Code.
2. Run cells top-to-bottom.

## Notes
This work was originally developed in an academic setting and later refactored for portfolio use.