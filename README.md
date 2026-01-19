# Heart Disease Prediction Using Logistic Regression and Random Forest

## Overview

This repository contains a machine learning project designed to predict the **presence of heart disease** in individuals based on clinical and demographic features using two classification models: **Logistic Regression** and **Random Forest**. The goal is to build, evaluate, and compare these models to determine which algorithm performs better on the chosen dataset. :contentReference[oaicite:2]{index=2}

## Table of Contents

- [Dataset](#dataset)  
- [Features](#features)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Modeling & Evaluation](#modeling--evaluation)  
- [Results](#results)  
- [Contributing](#contributing)  
- [License](#license)

## Dataset

The project uses the **Framingham Heart Study dataset** (commonly referred to as `framingham.csv`), which includes health metrics and lifestyle attributes for a cohort of patients. This dataset can be used to train and evaluate classification models that estimate the likelihood of heart disease. :contentReference[oaicite:3]{index=3}

### Example Attributes

Typical features in heart disease datasets include:

- Age  
- Gender  
- Blood Pressure  
- Cholesterol Level  
- Glucose Level  
- Smoking Status  
- Other clinical indicators

*(Adjust this list based on the actual columns in `framingham.csv`)*

## Installation

Clone the repository locally:

```bash
git clone https://github.com/Marghoob2000/Marghoob2000-Heart-Disease-Prediction-Using-Logistic-Regression-and-Random-Forest.git
cd Marghoob2000-Heart-Disease-Prediction-Using-Logistic-Regression-and-Random-Forest
```

Set up a Python environment (recommended):

```bash
python3 -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
```

Install dependencies:

```bash
pip install -r requirements.txt
```

(Create and populate `requirements.txt` based on the project packages such as pandas, scikit-learn, numpy, matplotlib, etc.)

## Usage

The main analysis and model training are performed in the provided Jupyter notebook:

```bash
jupyter notebook Heart_Disease_Prediction_Using_Logistic_Regression.ipynb
```

Inside the notebook, you will find steps for:

1. Loading and exploring the dataset
2. Preprocessing and cleaning the data
3. Splitting into training and testing sets
4. Training Logistic Regression and Random Forest models
5. Evaluating and comparing model performance (accuracy, confusion matrix, etc.)

## Modeling & Evaluation

Both classification models are implemented using scikit-learn:

- Logistic Regression – A statistical model used for binary classification problems.
- Random Forest Classifier – An ensemble learning method based on multiple decision trees.

Key evaluation metrics may include:

- Model accuracy
- Confusion matrix
- Precision / Recall / F1-Score
- ROC curve

## Results

| Model               | Accuracy |
| ------------------- | -------- |
| Logistic Regression | ~68%   |
| Random Forest       | ~90%   |
