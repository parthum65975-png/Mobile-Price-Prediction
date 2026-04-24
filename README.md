# 📱 Mobile Price Prediction (ML Project)

![Python](https://img.shields.io/badge/Python-3.10-blue)
![ML](https://img.shields.io/badge/Machine%20Learning-Scikit--Learn-orange)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Project](https://img.shields.io/badge/Type-Classification-blueviolet)

---

## 📌 Project Overview

This project predicts the **price range of mobile phones** using Machine Learning techniques.

A **custom dataset** was generated and used to train classification models.

---

## 🎯 Objective

- Predict mobile price category (0–3)
- Apply supervised learning
- Compare multiple ML models
- Evaluate performance using metrics

---

## 📊 Dataset Information

- Total Records: **1000**
- Features:
  - battery_power  
  - ram  
  - px_height  
  - px_width  
  - mobile_wt  
  - talk_time  
  - camera  

- Target:
  - `price_range` (0 = Low, 3 = Premium)

---

## 🔍 Exploratory Data Analysis (EDA)

- Checked dataset structure and summary  
- No missing values found  
- Visualizations used:
  - Histograms  
  - Bar Charts  
  - Heatmaps  

---

## 🤖 Models Implemented

- Logistic Regression  
- Random Forest  

---

## ⚖️ Model Comparison

| Model                | Accuracy |
|---------------------|----------|
| Logistic Regression | ~85–95%  |
| Random Forest       | ~95–100% |

👉 **Best Model: Random Forest**

---

## 📈 Evaluation Metrics

- Accuracy  
- Precision  
- Recall  
- F1-score  
- Confusion Matrix  

---

## 🧠 Performance Explanation

Random Forest performed better because:
- It handles complex patterns  
- Works well with feature interactions  
- Reduces overfitting using multiple trees  

---

## 🛠️ Technologies Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## 📁 Project Structure
