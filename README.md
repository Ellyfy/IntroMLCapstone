\# IntroMLCapstone



This repository contains code for the Capstone project:

\*\*Comparative Analysis of XGBoost and Polynomial Logistic Regression for Medical Diagnosis Prediction\*\*



\## Folder structure

\- `xgboost\_model.` — XGBoost implementation

\- `poly\_logistic\_model.ipynb` — Polynomial Logistic Regression (degree 2)

\- `baseline\_model.ipynb` — Standard Logistic Regression baseline

\- `paper1\_reproduction.ipynb` — Reproduction of MDPI paper

\- `paper2\_reproduction.ipynb` — Reproduction of arXiv paper

\- `models/` — Saved trained models and encoders



\## Dataset

\- `Diagnosis.xlsx` (Run 1) and `Diagnosis3.xlsx` (Run 2)

\- Features: Demographics, procedure codes, secondary diagnoses

\- Engineered features: Age, DOS\_Weekday, DOS\_Month

\- Target: D1 (primary diagnosis), grouped rare labels into 'Other'



\## Instructions

1\. Place your dataset in the same folder.

2\. Run each `.ipynb` file individually.

3\. Trained models will be saved to `models/`.

4\. Use `paper1\_reproduction.ipynb` and `paper2\_reproduction.ipynb` to compare approaches from literature.



\## Requirements

\- Python 3.8+

\- pandas, numpy, scikit-learn, xgboost, joblib, matplotlib, seaborn

