# Machine Learning Lab – Lab 5
## K-Nearest Neighbor (KNN) for Classification and Regression

![Python](https://img.shields.io/badge/Python-3.x-blue)
![Scikit--learn](https://img.shields.io/badge/Scikit--learn-KNN-orange)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-lightblue)
![Google Colab](https://img.shields.io/badge/Google%20Colab-Notebook-yellow)

---

## 👨‍🎓 Student Details

| Details | Information |
|---|---|
| **Name** | Gaurav Patel |
| **Roll No.** | 27 |
| **Section** | A |
| **Batch** | A2 |
| **Branch** | Artificial Intelligence & Machine Learning |
| **Lab** | Machine Learning |
| **Practical No.** | 5 |

---

## 🎯 Aim

**To implement K-Nearest Neighbor (KNN) algorithm for Classification and Regression.**

---

## 📌 Objective

The objective of this practical is to understand and implement the **K-Nearest Neighbor (KNN)** algorithm and evaluate its performance on a real-world dataset.

The practical covers:

- Understanding the working principle of KNN
- Loading and inspecting the dataset
- Data preprocessing
- Handling invalid zero values
- Median imputation
- Train-test splitting
- Feature scaling
- KNN classification
- Model evaluation
- Selection of an appropriate value of K
- Stratified K-Fold Cross-Validation
- Hyperparameter tuning using GridSearchCV
- Final model evaluation

The practical also explains the application of KNN for **regression**, although the supplied notebook implements the classification experiment.

---

# 📊 Dataset

The practical uses the **Diabetes Dataset**.

### Dataset Information

| Property | Value |
|---|---|
| Dataset Name | Diabetes Dataset |
| File Name | `diabetes.csv` |
| Number of Rows | 768 |
| Number of Columns | 9 |
| Input Features | 8 |
| Target Variable | `Outcome` |

### Features

The dataset contains the following input features:

1. `Pregnancies`
2. `Glucose`
3. `BloodPressure`
4. `SkinThickness`
5. `Insulin`
6. `BMI`
7. `DiabetesPedigreeFunction`
8. `Age`

### Target Variable

The target variable is:

```text
Outcome
