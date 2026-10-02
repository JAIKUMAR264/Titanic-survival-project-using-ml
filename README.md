# 🚢 Titanic Survival Prediction using Machine Learning

A machine learning classification project that predicts whether a passenger survived the Titanic disaster based on passenger and travel-related features.

## 📌 Project Overview

This project follows a complete machine learning workflow, starting from dataset exploration and preprocessing to training and evaluating multiple classification models.

The Titanic dataset used in this project contains 891 passenger records with features such as passenger class, gender, age, family information, fare, and embarkation details.

## 🎯 Objective

The main objective is to build a machine learning model that can predict the survival status of a Titanic passenger.

- `0` → Did not survive
- `1` → Survived

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Joblib
- Jupyter Notebook / Google Colab

## 🔄 Machine Learning Workflow

1. Dataset loading
2. Data exploration
3. Data preprocessing
4. Handling missing values
5. Categorical feature encoding
6. Feature and target separation
7. Train-test split
8. Feature scaling
9. Model training
10. Model evaluation
11. Cross-validation
12. Hyperparameter tuning

## 🤖 Machine Learning Models

The project experiments with multiple classification algorithms:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Gaussian Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)

## 📊 Model Evaluation

The models are evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- 5-Fold Cross-Validation

### KNN Hyperparameter Tuning

The value of `K` was evaluated from 1 to 21 using 5-fold cross-validation.

- **Best K:** 4
- **Average Cross-Validation Accuracy:** 82.70%

### SVM Evaluation

The SVM model uses an RBF kernel.

- **Test Accuracy:** 82.58%
- **Training Accuracy:** 83.68%
- **5-Fold Cross-Validation Accuracy:** 82.42%

## 📈 Results

### SVM Classification Report

| Class | Precision | Recall | F1-Score |
|-------|-----------|--------|----------|
| 0     | 0.84      | 0.88   | 0.86     |
| 1     | 0.80      | 0.74   | 0.77     |

**Test Accuracy:** 82.58%

**Training Accuracy:** 83.68%

**5-Fold Cross-Validation Accuracy:** 82.42%

## 📓 Notebook

The complete implementation is available in:

`titanic.ipynb`

The notebook contains the complete workflow including:

- Data exploration
- Data preprocessing
- Missing-value handling
- Feature encoding
- Feature scaling
- Model training
- Hyperparameter tuning
- Confusion matrices
- Classification reports
- Cross-validation

## ▶️ Run the Project

The notebook can be opened and executed using **Google Colab** or **Jupyter Notebook**.

### Google Colab

Open the notebook directly in Google Colab:

[Open Titanic Project in Google Colab](https://colab.research.google.com/github/JAIKUMAR264/Titanic-survival-project-using-ml/blob/main/titanic.ipynb)

## 📁 Project Structure

```text
Titanic-survival-project-using-ml/
│
├── titanic.ipynb
└── README.md
