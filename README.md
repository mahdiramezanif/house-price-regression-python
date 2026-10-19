# House Price Regression — Python Experiments

A small machine-learning learning project exploring **regression for house-price prediction**. It includes a Jupyter notebook for data exploration/model comparison and a separate Python script implementing the key steps of univariate linear regression.

## What's inside

- [`Jupiter_main_file.ipynb`](Jupiter_main_file.ipynb) — notebook for the house-price regression exercise (filename preserved as in the repository)
- [`auxiliaryFile.py`](auxiliaryFile.py) — manually implemented mean-squared-error cost, gradient calculations, and gradient descent

The original notebook description refers to an educational Boston housing dataset. This repository does **not** currently ship that dataset as a separate file.

## Core ideas
- Linear regression and model fitting
- Regression cost function
- Gradient descent from scratch
- Visualizing/comparing results in a notebook

## Run the notebook

```bash
python -m venv .venv
# Activate the virtual environment
pip install numpy pandas matplotlib scikit-learn jupyter
jupyter notebook Jupiter_main_file.ipynb
```

**Note:** The exact notebook dependency and data availability should be checked in the notebook before execution.

## Run the auxiliary script

```bash
python auxiliaryFile.py
```

The script additionally imports `lab_utils_uni` and a local Matplotlib style file, `deeplearning.mplstyle`, which **are not included in this repository**. Remove those optional imports or add the teaching resources before running it successfully.

## Purpose
A learning-focused implementation, not a production house-price estimator. No benchmark accuracy or reproducibility claim is made here.
