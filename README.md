# Regression-Based Age Prediction Model

This project was developed as part of the **Data Science Lab** course in the **Master’s Degree in Data Science and Engineering** at **Politecnico di Torino**. \it  applies machine learning regression techniques to predict a person's age based on voice and audio-related features.

The goal is to train and compare different regression models using structured audio data, evaluate their performance, and generate age predictions for an evaluation dataset.

---

## Project Overview

Age prediction from voice data is a regression problem where the model learns patterns from audio-related features such as pitch, jitter, shimmer, energy, pauses, speech length, and spectral characteristics.

The project includes data preprocessing, exploratory analysis, model training, model evaluation, and prediction generation.

---

## Dataset

The repository contains the following main files:

```text
development.csv
evaluation.csv
sample_submission.csv
```

The `development.csv` file contains the training data, including the target variable `age`.

The `evaluation.csv` file contains the data used to generate final age predictions.

---

## Repository Structure

```text
Regression-based-age-prediction-model/
│
├── Project.ipynb
├── development.csv
├── evaluation.csv
├── sample_submission.csv
├── Regression-based age prediction model.pdf
└── README.md
```

---

## Technologies Used

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- lightgbm

---

## Models Used

The project explores and compares several regression models, including:

- Linear Regression
- Ridge Regression
- Lasso Regression
- Random Forest Regressor
- XGBoost Regressor
- LightGBM Regressor

---

## Evaluation Metric

The main evaluation metric used in this project is **Root Mean Squared Error (RMSE)**.

RMSE is used to measure the average difference between the predicted ages and the real ages. A lower RMSE indicates better model performance.

---

## How to Run the Project

### 1. Clone the repository

```bash
git clone https://github.com/anaparovic/Regression-based-age-prediction-model.git
cd Regression-based-age-prediction-model
```

### 2. Install the required dependencies

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost lightgbm
```

### 3. Run the notebook

```bash
jupyter notebook Project.ipynb
```

Run the notebook cells sequentially to reproduce the analysis, train the models, and generate predictions.

---

## Results

The notebook compares different regression models and evaluates their performance using RMSE. Tree-based models such as Random Forest, XGBoost, and LightGBM are tested alongside linear regression models.

The final predictions are generated for the evaluation dataset and saved in CSV format.

---
