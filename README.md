# 🩺 Early Detection of Breast Cancer with Machine Learning
## Description
This project aims to detect breast cancer early by using machine learning techniques on the Wisconsin Breast Cancer Dataset. The goal is to build and compare multiple classification models to identify the presence of cancer cells with high accuracy.
# 🗂️ Data
The Wisconsin Breast Cancer Dataset contains features extracted from breast biopsies, such as:
- Cell texture, symmetry and concavity
- Cell nucleus size and shape
- Other relevant diagnostic measures
## The target label is binary:
* 0: Benign cells
* 1: Malignant cells
# ⚙️ Models Used
Models tested in this project include:
* ✅ Régression Logistique (Best model with 98% accuracy)
* ✅ k-Nearest Neighbors (KNN)
* ✅ Arbre de Décision
* ✅ Support Vector Machine (SVM) (High performance, 98% accuracy)
* ✅ Naive Bayes
* ✅ XGBoost

# 📊 Results and Comparison

The models were evaluated using the following metrics:

- Accuracy
- Recall
- F1-Score
  
- | Model                | Accuracy | Precision | Recall | F1-Score |
- | **Logistic Regression** | 0.98    | 0.98      | 0.98   | 0.98   |
- | Model                | Accuracy | Precision | Recall | F1-Score |
- | **KNN**               | 0.96    | 0.96      | 0.95   | 0.96     |
- | Model                | Accuracy | Precision | Recall | F1-Score |
- | **Decision Tree**     | 0.94    | 0.94      | 0.94   | 0.94     |
- | Model                | Accuracy | Precision | Recall | F1-Score |
- | **SVM**               | 0.98    | 0.98      | 0.97   | 0.98     |
- | Model                | Accuracy | Precision | Recall | F1-Score |
- | **Naive Bayes**       | 0.94    | 0.93      | 0.93   | 0.94     |
- | Model                | Accuracy | Precision | Recall | F1-Score |
- | **XGBoost**           | 0.97    | 0.97      | 0.97   | 0.97     |


# 🧠 Model Explainability

To understand the model decisions, we used LIME (Local Interpretable Model-agnostic Explanations) to explain the predictions of the classification models.
