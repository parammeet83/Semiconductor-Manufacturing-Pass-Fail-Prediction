# Semiconductor Manufacturing Pass/Fail Prediction using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![License](https://img.shields.io/badge/License-MIT-green)

## Project Overview

This project develops a Machine Learning-based classification system to predict whether a semiconductor manufacturing process results in a **Pass** or **Fail** outcome. The project focuses on data preprocessing, handling missing values, balancing the dataset, training multiple machine learning models, and selecting the best-performing model through evaluation and hyperparameter tuning.

---

## Problem Statement

Semiconductor manufacturing generates a large amount of sensor data during production. Detecting defective products manually is difficult and time-consuming. This project uses Machine Learning algorithms to automatically classify semiconductor products as **Pass** or **Fail**, helping improve manufacturing quality and efficiency.

---

## Dataset

- **Dataset Name:** SECOM (Semiconductor Manufacturing Process Dataset)
- **Total Samples:** 1,567
- **Target Variable:** Pass / Fail
- **Source:** UCI Machine Learning Repository

> Note: The dataset is publicly available from the UCI Machine Learning Repository and is therefore not included in this repository.

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- imbalanced-learn (SMOTE)

---

## Machine Learning Models

The following classification models were implemented:

- Random Forest Classifier
- Gaussian Naive Bayes
- Support Vector Machine (SVM)
- Optimized Support Vector Machine (GridSearchCV)

---

## Data Preprocessing

The following preprocessing techniques were applied:

- Removed unnecessary columns
- Handled missing values
- Removed features with excessive missing values
- Balanced the dataset using SMOTE
- Feature scaling using StandardScaler
- Train-Test Split (80:20)

---

## Model Performance

| Model | Test Accuracy |
|-------|--------------:|
| Random Forest | **92.99%** |
| Gaussian Naive Bayes | **25.48%** |
| Support Vector Machine | **93.31%** |
| Optimized SVM | **93.63%** |

The optimized Support Vector Machine achieved the highest prediction accuracy after hyperparameter tuning using GridSearchCV.

---

## Repository Structure

```
Semiconductor-Manufacturing-Pass-Fail-Prediction
│
├── notebook/
├── report/
├── presentation/
├── models/
├── dataset/
├── images/
├── README.md
├── LICENSE
└── .gitignore
```

---

## How to Run

1. Clone this repository.
2. Install the required Python libraries.
3. Open the notebook in Google Colab or Jupyter Notebook.
4. Execute the notebook cells sequentially.
5. Train the model and evaluate the results.

---

## Future Scope

- Implement Deep Learning models.
- Deploy the model as a web application.
- Perform advanced feature engineering.
- Evaluate the model using larger industrial datasets.

---

## Author

**Parammeet**

B.Tech (Computer Science and Engineering)

Birla Institute of Technology Mesra, Off Campus Deoghar

---

## Internship

This project was completed as part of the **Corizo Summer Training and Internship Program** in Machine Learning.

---

## License

This project is released under the **MIT License**.
