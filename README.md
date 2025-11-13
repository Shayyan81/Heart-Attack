# Heart Attack Prediction using Machine Learning

This project focuses on **predicting heart attacks** using patient data and machine learning techniques. 

## 🧠 Project Overview
- **Dataset:** Heart Disease dataset (UCI / custom dataset)  
- **Goal:** Predict whether a patient is at risk of a heart attack based on clinical features.  
- **Key Features:** Age, sex, chest pain type (cp), resting blood pressure (trtbps), cholesterol (chol), maximum heart rate (thalachh), number of blocked arteries (caa), ST depression (oldpeak), and more.

## 🛠️ Methodology
- **Model Used:** Random Forest Classifier  
- **Training/Test Split:** 80/20  
- **Evaluation Metrics:** Accuracy, Confusion Matrix, Feature Importance  
- **Visualizations:** Pairplot, Violin plots, Confusion Matrix heatmap

## 📊 Results
- **Test Accuracy:** 83.6%  
- Important features influencing predictions include `caa`, `oldpeak`, `thalachh`, `cp`, and `thall`.  
- Visualizations help understand feature distribution and class separation.

## 🚀 Usage
1. Clone the repository  
```bash
git clone <your-repo-link>
