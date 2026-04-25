# Projet_ARNN

## Overview

`Projet_ARNN` is a machine learning repository focused on two core projects:

- `classification`: A notebook-based workflow for classifying stars using neural networks and traditional classifiers.
- `regression`: A notebook-based workflow for life expectancy prediction using linear, polynomial, and advanced regression models.

The repository contains exploratory data analysis, preprocessing, model training, comparison, and prediction outputs.

## Repository Structure

- `classification/`
  - `01_data_exploration_preprocessing.ipynb` — data exploration and preprocessing for star classification.
  - `02_knn_decision_tree.ipynb` — baseline classification with KNN and decision tree models.
  - `03_neural_network.ipynb` — neural network model training and evaluation.
  - `04_model_comparison.ipynb` — comparison of classification model performance.
  - `star_classification.csv` — dataset for star classification.
  - `data/` — auxiliary data files used by classification notebooks.
  - `models/` — saved classification models (for example `fnn_model.keras`).
  - `predictions/` — classification prediction outputs.

- `regression/`
  - `01_data_exploration_preprocessing.ipynb` — life expectancy data exploration and preprocessing.
  - `02_linear_polynomial_regression.ipynb` — linear and polynomial regression modeling.
  - `03_advanced_models.ipynb` — more advanced regression approaches.
  - `04_model_comparison.ipynb` — comparison of regression model performance.
  - `Life Expectancy Data.csv` — dataset for regression tasks.
  - `data/` — auxiliary data files used by regression notebooks.
  - `predictions/` — regression prediction outputs.

## Getting Started

1. Install Python and Jupyter Notebook or JupyterLab.
2. Install the required Python packages, for example:

```bash
pip install numpy pandas matplotlib scikit-learn tensorflow jupyter
```

3. Open the repository in Jupyter and run the notebooks in order.

## Notes

- The notebooks are designed for exploratory analysis and model experimentation.
- Data preprocessing and feature engineering are performed within the notebooks.
- The repository includes both traditional machine learning and neural network approaches.
