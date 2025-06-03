# 🌾 Smart Fertilizer Prediction using XGBoost for Crop Yield Optimization

This project uses an XGBoost classifier to predict the optimal fertilizer based on environmental and soil conditions. The goal is to assist farmers in making data-driven decisions for maximizing crop yield.

---

## 🎯 Objective

- Predict the most suitable fertilizer for a given crop using machine learning.
- Use soil nutrient levels and climatic factors for accurate predictions.
- Enhance agricultural productivity through data science.

---

## 📊 Dataset Overview

The dataset includes various features relevant to soil and climate:

| Feature       | Description                              |
|---------------|------------------------------------------|
| N             | Nitrogen content in the soil             |
| P             | Phosphorus content in the soil           |
| K             | Potassium content in the soil            |
| Temperature   | Ambient temperature                      |
| Humidity      | Relative humidity (%)                    |
| pH            | pH value of the soil                     |
| Rainfall      | Rainfall (mm)                            |
| Crop Type     | Crop name (categorical feature)          |
| Fertilizer    | Target variable (fertilizer label)       |

---

## 🧠 Model Details

- **Algorithm**: XGBoost Classifier
- **Why XGBoost?**
  - High performance
  - Handles categorical and numerical data well
  - Offers feature importance and early stopping

### 🔧 Data Preprocessing

- Label Encoding for Crop Type
- Feature Selection
- Train-test split
- Optional: Normalization/Standardization

### 📈 Model Evaluation

| Metric         | Value (Example)     |
|----------------|---------------------|
| Accuracy       | ~92%                |
| Log Loss       | ~0.21               |
| F1-Score       | High                |
| Confusion Matrix | Used for class-level validation |

> A **Log Loss** value around 0.2 indicates strong probabilistic confidence. Values above 1.0 typically suggest poor performance.

---

## 🧪 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/smart-fertilizer-xgboost.git
cd smart-fertilizer-xgboost
