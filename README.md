# IMDb Movie Rating Prediction 🎬

## README.md

```markdown
# IMDb Movie Rating Prediction 🎬

A Machine Learning project that predicts IMDb movie ratings using movie metadata such as genre, director, and actors. This project demonstrates data preprocessing, encoding categorical features, and building a regression model using Python.

---

## 📌 Project Overview

This project uses the IMDb India Movies dataset to analyze movie information and predict movie ratings.

The project workflow includes:
- Data Cleaning
- Handling Missing Values
- Feature Selection
- Label Encoding
- Train-Test Splitting
- Machine Learning Model Training
- Model Evaluation

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```

IMDb-Movie-Rating-Prediction/
│
├── IMDb_Movie_Rating_Prediction.ipynb
├── IMDb Movies India.csv
├── requirements.txt
├── .gitignore
├── LICENSE
└── README.md

````

---

## 📊 Dataset Information

The dataset contains:
- Genre
- Director
- Actor 1
- Actor 2
- Actor 3
- IMDb Rating

The dataset is used to train a machine learning model that predicts movie ratings based on these features.

---

## ⚙️ Data Preprocessing Steps

### ✔ Handling Missing Values
- Removed rows containing missing values using `dropna()`

### ✔ Feature Encoding
- Converted categorical columns into numerical format using `LabelEncoder`

### ✔ Feature Selection
Selected important features:
- Genre
- Director
- Actor 1
- Actor 2
- Actor 3

Target variable:
- Rating

---

## 🤖 Machine Learning Workflow

The project follows these steps:
1. Load Dataset
2. Clean Data
3. Encode Features
4. Split Dataset into Training and Testing Sets
5. Train Machine Learning Model
6. Evaluate Model Performance

---

## 📈 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.preprocessing import LabelEncoder
from sklearn.model_selection import train_test_split
````

---

