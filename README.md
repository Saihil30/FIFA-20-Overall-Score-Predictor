# 🎮 FIFA 20 Overall Score Predictor

Welcome to the FIFA 20 Overall Score Predictor project!  
This project analyses FIFA 20 player data and allows users to predict an overall FIFA score based on various player attributes.

---

## 📖 Overview

This project involves:
- 📊 Performing **Exploratory Data Analysis (EDA)** on FIFA 20 player statistics
- 🧠 Building **Regression Models** (Linear, Ridge, Lasso, Random Forest)
- 🚀 Deploying a simple **Streamlit App** to predict player scores interactively

---

## 📈 Results

Out of all tested models, the **Random Forest Regressor** performed best:
- ✅ **R² Score:** 97%
- ✅ **Root Mean Squared Error (RMSE):** 1.26

---

## 🛠️ How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/Saihil30/FIFA-20-Overall-Score-Predictor.git
cd FIFA-20-Overall-Score-Predictor
```
---

2. Install dependencies:
```bash
pip install -r requirements.txt
```
---

3. Open the Jupyter Notebook:
```bash
jupyter notebook fifa_prediction_final.ipynb
```
---

## 📦 Project Structure
📁 data
    └── players_20.csv
📁 notebooks
    └── fifa_prediction_final.ipynb
requirements.txt
README.md

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Streamlit

---

## 🚀 Next Steps
- 🛠️ Implement Hyperparameter Tuning (e.g., GridSearchCV) to optimise model performance
- 🎯 Expand the project to predict **player potential ratings** alongside overall score
- 📊 Perform **player clustering** (e.g., attackers, midfielders, defenders) using K-Means
- 🌎 Deploy the Streamlit app publicly via Streamlit Cloud for live user interaction
- 🔎 Add feature importance analysis (e.g., which attributes impact overall score most)
- 🏆 Explore adding player position or nationality as new features

---

## 📝 License
This project is licensed under the [MIT License](https://choosealicense.com/licenses/mit/).

---

