<div align="center">

# 🏥 Insurance Cost Prediction

**Predict individual medical insurance charges from age, BMI, smoking status and region using a stacked regression ensemble.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![CatBoost](https://img.shields.io/badge/CatBoost-FFCC00?logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?logo=scikitlearn&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?logo=jupyter&logoColor=white)

</div>

---

## ✨ Overview

`t.ipynb` uses `insurance.csv` and:

- 🔎 Explores the data with pandas / Seaborn.
- 🏷️ Encodes the categorical features `sex`, `smoker` and `region` with a `ColumnTransformer`.
- 🤖 Trains **Linear Regression, Linear SVR, Gradient Boosting and CatBoost** regressors.
- 🧱 Combines them with a **`StackingRegressor`** for the final prediction.

## 🚀 Getting Started

```bash
git clone https://github.com/Arashomranpour/insurance-cost.git
cd insurance-cost
pip install pandas numpy matplotlib seaborn scikit-learn catboost jupyter
jupyter notebook t.ipynb
```

## 📁 Project Structure

```
.
├── t.ipynb          # EDA, preprocessing, models, stacking
└── insurance.csv    # Dataset
```

## 🛠️ Tech Stack

`scikit-learn` · `CatBoost` · `pandas` · `Seaborn` · `Matplotlib`
