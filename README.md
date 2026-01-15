# Flight Delays 

A data analytics & machine learning project built in Python to predict **flight arrival delays (≥15 minutes)** and analyze the key operational and temporal factors influencing them.  
This repository is combining exploratory data analysis (EDA), feature engineering, model training, and explainability using SHAP.

---

## Project Overview

Flight delays are a persistent challenge for both passengers and airlines, resulting in billions of dollars in losses each year.  
The goal of this project is to:

1. Explore large-scale U.S. domestic flight data from the **U.S. Department of Transportation (US DOT)**.
2. Understand key patterns and seasonal trends affecting flight punctuality.
3. Build a predictive model to estimate the likelihood of a flight being delayed by 15+ minutes.
4. Interpret the model using SHAP to identify the most influential features.

---

## Dataset

- **Source:** [Kaggle - US DOT Flight Delays](https://www.kaggle.com/datasets/usdot/flight-delays)  
- **Scope:** Millions of domestic flight records across U.S. carriers and airports.  
- **Files include:** flight details, airline codes, departure/arrival delays, and route information.  


##  Repository Structure
flight-delays-ml/
├── src/
│   └── flight_delays.ipynb     # main notebook (EDA + modeling + evaluation)
├── data/
│   ├── raw/                    
│   └── processed/              
├── reports/
│   └── figures/              
├── .vscode/                    
├── requirements.txt          
├── README.md
├── LICENSE
└── .gitignore

## Tech Stack

| Category | Tools / Libraries |
|-----------|------------------|
| **Language** | Python 3.12 |
| **Data Handling** | Pandas, NumPy, PyArrow |
| **Visualization** | Matplotlib, Seaborn, Plotly |
| **Machine Learning** | scikit-learn, XGBoost |
| **Explainability** | SHAP |
| **Environment** | VS Code + Jupyter |
