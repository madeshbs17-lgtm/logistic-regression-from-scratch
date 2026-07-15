# 📊 Logistic Regression From Scratch

A complete implementation of **Logistic Regression** from scratch using **Python** and **NumPy**, without relying on machine learning libraries such as `scikit-learn` for model training.

This project demonstrates the complete workflow of a binary classification model, including feature standardization, gradient descent optimization, prediction, and performance evaluation on the **Diabetes Dataset**.

---

## 📖 Project Overview

The objective of this project is to understand the inner workings of Logistic Regression by implementing the algorithm from scratch.

Instead of using `sklearn.linear_model.LogisticRegression`, this implementation manually performs:

- Parameter initialization
- Sigmoid activation
- Gradient Descent optimization
- Weight and bias updates
- Prediction
- Model evaluation

The trained model is then used to classify whether a patient is diabetic based on medical diagnostic measurements.

---

## 🚀 Features

- Logistic Regression implemented from scratch
- Sigmoid activation function
- Gradient Descent optimization
- Custom `fit()` method
- Custom `predict()` method
- Feature Standardization
- Train-Test Split
- Binary Classification
- Accuracy Evaluation

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 📂 Project Structure

```
logistic-regression-from-scratch/
│
├── Logistic_Regression_From_Scratch.ipynb
├── diabetes.csv
├── README.md
└── requirements.txt
```

---

## 📊 Dataset

**Dataset:** Diabetes Dataset

### Input Features

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age

### Target Variable

- Outcome
  - **0** → Non-Diabetic
  - **1** → Diabetic

---

## ⚙️ Workflow

```
Load Dataset
      │
      ▼
Data Preprocessing
      │
      ▼
Feature Standardization
      │
      ▼
Train-Test Split
      │
      ▼
Initialize Weights & Bias
      │
      ▼
Forward Propagation
      │
      ▼
Sigmoid Function
      │
      ▼
Gradient Descent
      │
      ▼
Update Parameters
      │
      ▼
Prediction
      │
      ▼
Model Evaluation
```

---

## 🧠 Algorithm

This project implements Logistic Regression from scratch using:

- Sigmoid Function
- Gradient Descent
- Weight and Bias Updates
- Binary Classification
- Threshold-based Prediction

---

## 📈 Model Performance

The model was evaluated using **Accuracy Score**.

| Dataset | Accuracy |
|----------|----------:|
| Training Data | **77.69%** |
| Test Data | **76.62%** |

The model achieved an accuracy of **76.62%** on the test dataset, demonstrating its ability to classify diabetes outcomes using a Logistic Regression algorithm implemented entirely from scratch.

---

## ▶️ Installation

Clone the repository

```bash
git clone https://github.com/madeshbs17-lgtm/logistic-regression-from-scratch.git
```

Navigate to the project

```bash
cd logistic-regression-from-scratch
```

Install the required packages

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
Logistic_Regression_From_Scratch.ipynb
```

---

## 📚 Learning Outcomes

Through this project, I gained practical experience with:

- Binary Classification
- Logistic Regression
- Sigmoid Function
- Gradient Descent Optimization
- Feature Standardization
- Model Training from Scratch
- Machine Learning Fundamentals

---

## 👨‍💻 Author

**Madesh**

GitHub: https://github.com/madeshbs17-lgtm

---

⭐ If you found this project useful, consider giving it a star!
