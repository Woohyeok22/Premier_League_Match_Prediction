
# Premier League Match Prediction

## 📌 Project Overview
This project aims to predict English Premier League match results using machine learning models.

The goal is to classify match outcomes into three categories:
- Home Win (H)
- Draw (D)
- Away Win (A)

## 📊 Dataset
- Dataset: England_PremierLeague.csv
- Number of matches: 12,153
- Number of features: 25
- Target variable: FT_Result
  - Away Win: 0
  - Draw: 1
  - Home Win: 2

## 🛠️ Tools & Environment
- Google Colab
- R
- Machine Learning

## 🤖 Models & Methods
- Random Forest
- Support Vector Machine (SVM)
- Data preprocessing
- Train/Test Split (90:10)
- Model evaluation and comparison

## 📈 Model Performance

| Model | Accuracy |
|---|---:|
| Random Forest | 64.02% |
| SVM (Radial) | 60.81% |

- Random Forest OOB Error: 36.66%
- Random Forest Kappa: 0.4323

## 🔍 Key Considerations
- Removed full-time home and away goals (FTHG, FTAG) to prevent data leakage.
- Analyzed the relationship between match statistics, such as shots and shots on target, and match outcomes.
- Compared different machine learning models to evaluate prediction performance.

## 👨‍💻 My Role
- Data preprocessing and feature selection
- Machine learning model development
- Random Forest and SVM model implementation
- Model performance evaluation and comparison
- Analysis of factors associated with match outcomes

## 💻 Execution
The project was developed and executed entirely in Google Colab.

