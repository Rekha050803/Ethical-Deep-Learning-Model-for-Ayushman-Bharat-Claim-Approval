# Ethical Deep Learning Model for Ayushman Bharat Claim Approval

This project predicts healthcare insurance claim approvals under the **Ayushman Bharat Pradhan Mantri Jan Arogya Yojana (AB-PMJAY)** using a deep learning model. It emphasizes **fairness**, **explainability**, and **responsible AI**.

## 🚀 Project Highlights

- **Objective**: Predict claim approval using patient and hospital features.
- **Data Features**: Age, Gender, State, Hospital Type, Procedure, Preauth Approved, Claim Amount, etc.
- **Model**: Feedforward Neural Network (TensorFlow) with ReLU, Dropout, and Sigmoid layers.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-score.

## 🧠 Explainable AI

- **Tool Used**: SHAP (SHapley Additive exPlanations)
- **Insight**: Identified key feature impacts (e.g., State, Procedure, Hospital Type)

## ⚖️ Bias Detection & Fairness

- **Bias Detected**: Gender and hospital type disparities
- **Metrics Used**: Disparate Impact, Equal Opportunity Difference
- **Fairness Intervention**:
  - SMOTE for class balancing
  - Fairlearn’s ExponentiatedGradient with DemographicParity & EqualizedOdds

## ✅ Final Model Results

- **Accuracy**: 87%
- **F1-Score**: 0.87
- **Fairness**: Achieved equal recall (1.0) across gender & hospital types

## 📈 Tools & Libraries

- TensorFlow
- SHAP
- Fairlearn
- Scikit-learn
- Pandas
- NumPy

## 📎 Colab Notebook

[👉 View on Google Colab](https://colab.research.google.com/drive/1MvtrrtM2tH6clh2VWIdxnV1hrXGcQl6D?usp=sharing)
