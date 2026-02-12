# Level 1

Level 1 establishes foundational skills in data preprocessing and classification modeling.

---

## 📌 Task 1: Data Preprocessing

Dataset: `churn-bigml-80.csv`

### 🎯 Objective
Prepare a raw dataset so that it becomes suitable for machine learning models.

### 🔍 Steps Performed:
- Inspected dataset structure and data types
- Identified and handled missing values
- Encoded categorical variables using One-Hot Encoding
- Scaled numerical features using StandardScaler
- Split dataset into training and testing sets (80/20)

### 📊 Outcome
- Cleaned and transformed dataset ready for modeling
- Improved feature consistency through scaling
- Created a reusable preprocessing workflow


The dataset was cleaned and prepared for machine learning modeling.

---

## 📌 Task 3: K-Nearest Neighbors (KNN)

Dataset: `iris.csv`

### 🎯 Objective
Build and evaluate a KNN classifier to predict flower species.

### 🔍 Steps Performed
- Loaded and explored the Iris dataset
- Scaled features using StandardScaler
- Trained KNN model with different values of K
- Evaluated model using Accuracy, Precision, Recall
- Visualized performance using a Confusion Matrix
- Compared multiple K values to determine optimal performance
- Model saving using joblib

### 📊 Results
- Best K Value: 3 (Accuracy remained 1.0 across multiple K values)
- Final Accuracy: 1.0

The model demonstrates strong performance on multi-class classification tasks.

---

Level 1 successfully demonstrates fundamental machine learning workflow.

