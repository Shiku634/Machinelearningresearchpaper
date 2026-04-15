# 🏠 House Price Prediction using Machine Learning

## 📌 Project Title
Predicting House Prices using Machine Learning Models: A Comparative Study

---

## 📖 Overview

This project presents a comprehensive analysis of various machine learning algorithms for predicting house prices using real-world housing data.

The study evaluates both traditional statistical methods and advanced machine learning models to determine the most effective approach for accurate price prediction.

---

## 🎯 Objectives

- Predict house prices based on multiple features
- Compare performance of different ML models
- Analyze factors influencing real estate prices
- Improve prediction accuracy using advanced algorithms

---

## 🛠 Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📊 Dataset

- Source: Kaggle Housing Dataset
- Features include:
  - Area
  - Bedrooms
  - Bathrooms
  - Stories
  - Parking
  - Air Conditioning
  - Furnishing Status

---

## ⚙️ Methodology

### 🔹 Data Preprocessing
- Handling missing values
- Outlier removal
- Feature scaling
- Encoding categorical variables

### 🔹 Models Implemented
- Linear Regression
- Ridge Regression
- Random Forest Regressor
- Support Vector Regressor (SVR)
- XGBoost Regressor
- Logistic Regression (for classification analysis)

### 🔹 Evaluation Metrics
- R² Score
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- Mean Absolute Error (MAE)

---

## 📈 Results & Insights

- Multivariate regression significantly improved accuracy (~61.97%)
- Area, bathrooms, and air conditioning are key influencing factors
- XGBoost outperformed all other models in terms of accuracy and robustness
- Linear models are interpretable but limited in handling complex relationships

---

## 📊 Visualizations

- Correlation Matrix
- Pairplots
- Price Distribution Histogram
- Model Prediction Comparison Graphs

---

## 📄 Research Paper

Full research paper available in `/paper` directory.

---

## 🚀 How to Run

```bash
git clone https://github.com/YOUR_USERNAME/house-price-prediction-ml.git
cd house-price-prediction-ml
pip install -r requirements.txt
jupyter notebook
