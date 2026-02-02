# End-to-End Machine Learning Project

This repository contains an **end-to-end machine learning workflow**, demonstrating how to build, train, and evaluate ML models using Python. It includes notebooks, scripts, and supporting files to run experiments and produce reusable model artifacts.

---

## 🧠 Project Overview

The project covers the full ML lifecycle:

- **Data preprocessing** – Cleaning and transforming raw data for modeling.
- **Model training** – Scripts and notebooks for training models, including CatBoost and other ML algorithms.
- **Model evaluation** – Metrics and visualizations to assess performance.
- **Model artifacts** – Saved models and supporting files in the `artifacts/` folder.
- **Reusable code** – Modularized Python code in `src/` for ease of extension.

---
### Install dependencies

pip install -r requirements.txt

1. Running Notebooks

Open Jupyter Notebook or JupyterLab:

jupyter notebook

2. Running Scripts

### Training a model:

python src/train_model.py

### Evaluating a model:

python src/evaluate_model.py


Adjust paths and parameters as needed depending on your dataset.

📦 Model Artifacts

Trained models are saved in the artifacts/ folder.

CatBoost-specific metadata is stored in catboost_info/.

You can load these models in scripts or notebooks for predictions.
