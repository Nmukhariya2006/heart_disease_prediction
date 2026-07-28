# ❤️ Heart Disease Prediction using Machine Learning



# 📖 Table of Contents
 Project Overview
- Problem Statement
- Features
- Dataset
- Machine Learning Pipeline
- Data Preprocessing
- Exploratory Data Analysis
- Models Used
- Hyperparameter Tuning
- Model Evaluation
- Technologies Used
- Project Structure
- Installation
- Usage
- Results
- Future Improvements
- Author

---

# ❤️ Project Overview

Heart Disease is one of the leading causes of death worldwide. Early prediction can help doctors diagnose patients faster and provide timely treatment.

This project builds an end-to-end Machine Learning pipeline that predicts whether a patient is likely to have heart disease using clinical information.

The project demonstrates the complete Data Science workflow:

- Data Cleaning
- Feature Engineering
- Exploratory Data Analysis
- Data Preprocessing
- Machine Learning
- Model Evaluation
- Hyperparameter Tuning

---

# 🎯 Problem Statement

Develop a Machine Learning model capable of predicting heart disease using patient medical attributes.

The goal is to assist healthcare professionals by providing an accurate prediction model.


# ✨ Features

✔ Data Cleaning

✔ Missing Value Handling

✔ Feature Engineering

✔ Exploratory Data Analysis

✔ Data Visualization

✔ Machine Learning Pipelines

✔ Model Comparison

✔ Hyperparameter Tuning

✔ ROC Curve

✔ Confusion Matrix

✔ Classification Report

---

# 📊 Dataset

The dataset contains medical records including:

- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Resting ECG
- Maximum Heart Rate
- Exercise Induced Angina
- ST Depression
- Slope
- Number of Major Vessels
- Thalassemia
- Target Variable (Heart Disease)

---

# ⚙ Machine Learning Pipeline

The project follows the complete ML lifecycle:

```
Dataset
    │
    ▼
Data Cleaning
    │
    ▼
Missing Value Imputation
    │
    ▼
Feature Encoding
    │
    ▼
Feature Scaling
    │
    ▼
Train/Test Split
    │
    ▼
Model Training
    │
    ▼
Hyperparameter Tuning
    │
    ▼
Evaluation
```

---

# 🧹 Data Preprocessing

The notebook performs:

- Handling Missing Values
- Column Renaming
- Numerical Feature Scaling
- Categorical Encoding
- Train-Test Split
- Pipeline Creation using Scikit-Learn

Preprocessing tools:

- SimpleImputer
- StandardScaler
- OneHotEncoder
- ColumnTransformer
- Pipeline

---

# 📈 Exploratory Data Analysis

The notebook includes:

- Dataset Information
- Statistical Summary
- Missing Value Analysis
- Feature Inspection
- Data Visualization

---

# 🤖 Machine Learning Models

Three different models were trained.

| Model | Description |
|--------|-------------|
| Logistic Regression | Linear Classification |
| Random Forest | Ensemble Learning |
| Support Vector Classifier | Margin-based Classification |

---

# 🔥 Hyperparameter Tuning

Random Forest was optimized using:

- GridSearchCV
- Cross Validation
- Parameter Search

Parameters include:

- Number of Trees
- Maximum Depth
- Minimum Samples Split
- Minimum Samples Leaf

---

# 📊 Model Evaluation

Evaluation metrics used:

- Accuracy
- Classification Report
- Confusion Matrix
- ROC Curve
- ROC-AUC Score

The notebook also compares model performances using a summary table.

---

# 🛠 Technologies Used

| Technology | Purpose |
|------------|----------|
| Python | Programming |
| Pandas | Data Analysis |
| NumPy | Numerical Computing |
| Matplotlib | Visualization |
| Scikit-Learn | Machine Learning |
| GridSearchCV | Hyperparameter Tuning |

---

# 📂 Project Structure

```
heart_disease_prediction
│
├── heart_disease_prediction.ipynb
├── heart_disease_uci.csv
├── README.md
└── requirements.txt
```

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Nmukhariya2006/heart_disease_prediction.git
```

Move into the project

```bash
cd heart_disease_prediction
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run Jupyter Notebook

```bash
jupyter notebook
```

---

# ▶ Usage

Open

```
heart_disease_prediction.ipynb
```

Run every notebook cell sequentially to:

- Load Dataset
- Preprocess Data
- Train Models
- Evaluate Performance
- Compare Results

---

# 📈 Results

The notebook compares:

- Logistic Regression
- Random Forest
- Support Vector Classifier

Random Forest is further optimized using GridSearchCV for improved performance.

---

# 🔮 Future Improvements

- Deploy using Streamlit
- Flask/FastAPI API
- Docker Support
- Model Explainability using SHAP
- Deep Learning Model
- XGBoost
- LightGBM
- CatBoost
- Feature Importance Dashboard

---



