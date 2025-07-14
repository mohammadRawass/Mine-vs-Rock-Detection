# 🔍 Mines vs Rocks Detection using Machine Learning

This project is a binary classification task using the **Sonar dataset**, which contains sonar signal returns from metal cylinders (mines) and rocks. The goal is to predict whether a given sonar reading corresponds to a **mine** or a **rock** using supervised machine learning algorithms.

---

## 📁 Dataset

- **Source**: UCI Machine Learning Repository
- **Features**: 60 continuous attributes (sonar signal strength)
- **Target**: `M` (Mine) or `R` (Rock)

---

## 🚀 Objectives

1. Perform data cleaning and exploratory data analysis (EDA)
2. Scale features for optimal model performance
3. Train and evaluate multiple classification models
4. Tune model hyperparameters
5. Compare results and draw conclusions

---

## ✅ Workflow

1. **Importing & Inspecting Data**:
   - Checked for null values and explored distribution.
2. **Feature Scaling**:
   - Applied `StandardScaler` to standardize the dataset.
3. **Train/Test Split**:
   - Used 75% for training, 25% for testing.
4. **Model Training**:
   - Implemented **K-Nearest Neighbors (KNN)**
   - Implemented **Support Vector Machine (SVM)**
5. **Hyperparameter Tuning**:
   - Tried different `n_neighbors` for KNN and kernel/C values for SVM.
6. **Model Evaluation**:
   - Used accuracy, precision, recall, F1-score, and confusion matrix to assess performance.
7. **Model Comparison**:
   - Compared models side-by-side to determine the most effective one.

---

## 📊 Results Summary

| Model | Accuracy | Comments |
|-------|----------|----------|
| KNN   | 92%      | Sensitive to `k` value. Performed well overall. |
| SVM   | 94%      | Showed better precision and recall with RBF kernel. |

---

## 📌 Key Takeaways

- Scaling was critical due to distance-based algorithms like KNN and SVM.
- SVM slightly outperformed KNN in most metrics.
- A final comparison and confusion matrix visuals clarified model strengths.

---
