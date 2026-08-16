# CSC3173: Artificial Intelligence (2024/25)

## Programming Assignment 01

**Registration Number:** S/21/513

### Customer Churn Prediction: XGBoost vs Multilayer Perceptron (MLP)

This project implements a complete binary-classification pipeline for predicting customer churn using **XGBoost** and a **Multilayer Perceptron (MLP)** neural network.

The two models are optimized and evaluated using common classification metrics including:

- Accuracy
- Precision
- Recall
- F1-score

## Dataset

**Dataset:** IBM Telco Customer Churn

**Source:** Kaggle - [`yeanzc/telco-customer-churn-ibm-dataset`](https://www.kaggle.com/datasets/yeanzc/telco-customer-churn-ibm-dataset?select=Telco_customer_churn.xlsx)

The dataset contains telecommunications customer information that is used to predict whether a customer is likely to churn.

## Project Structure

```text
assignment_01/
├── data/
│   └── Telco_customer_churn.xlsx
├── notebooks/
│   └── teleco_customer_churn.ipynb
├── README.md
├── pyproject.toml
└── uv.lock
```

## Environment

The project uses **Python 3.12** and [`uv`](https://docs.astral.sh/uv/) for dependency and virtual-environment management.

Main libraries include:

- TensorFlow / Keras
- XGBoost
- scikit-learn
- SciKeras
- Pandas
- NumPy
- Matplotlib
- Joblib
- OpenPyXL

## Setup

Install the project dependencies:

```bash
uv sync
```

Start JupyterLab:

```bash
uv run jupyter lab
```

Then open:

```text
notebooks/teleco_customer_churn.ipynb
```

Run the notebook cells sequentially from the beginning.

## Notebook Workflow

The notebook covers:

1. Dataset loading and inspection
2. Data cleaning and preprocessing
3. Feature preparation
4. Train-test splitting
5. XGBoost model development
6. XGBoost hyperparameter optimization
7. MLP model development
8. MLP hyperparameter optimization
9. Model evaluation
10. Comparison of XGBoost and MLP performance

## Author

**Sivothayan** - **S/21/513**
