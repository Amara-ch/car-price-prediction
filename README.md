# car-price-prediction
# 🚗 Car Price Prediction - Professional Notebook  

A machine learning project for predicting car prices using advanced preprocessing techniques, missing value handling, brand cleaning, and regression model comparison.

This project demonstrates how to handle real-world car datasets with incomplete and inconsistent data while building accurate predictive models.

---

## 📌 Project Overview  

The goal of this project is to predict car prices using machine learning regression techniques.

Key challenges addressed:

- Handling missing numerical and categorical values  
- Cleaning inconsistent brand names  
- Encoding categorical variables  
- Comparing regression models  
- Evaluating performance using multiple metrics  

---

## 📂 Dataset Features  

The dataset includes:

- **Brand**  
- **Model**  
- **Year**  
- **Engine Size**  
- **Fuel Type**  
- **Transmission**  
- **Mileage**  
- **Doors**  
- **Owner Count**  
- **Price (Target Variable)**  

---

## 🔧 Data Preprocessing  

### Missing Value Handling
Real-world datasets often contain missing values. This notebook handles them professionally:

- Numerical columns → **Median Imputation**  
- Categorical columns → **Mode Imputation**  

### Brand Cleaning
Standardized inconsistent brand names by:

- Removing extra spaces  
- Fixing capitalization  
- Cleaning duplicate variations  

Example:

```python
"toyota", "Toyota ", " TOYOTA" → "Toyota"
```

### Feature Encoding
Applied encoding techniques for categorical data:

- Label Encoding  
- One-Hot Encoding  

### Feature Scaling
Used:

- StandardScaler  

for normalization of numerical features.

---

## 🤖 Models Used  

Two regression models were trained and compared:

### 1. Linear Regression
A baseline model for understanding linear relationships.

### 2. Random Forest Regressor
An ensemble model for better accuracy and non-linear pattern capture.

---

## 📊 Model Performance  

### Linear Regression Results

| Metric | Score |
|--|--|
| R² Score | **0.9121** |
| MAE | **1768.54** |

---

### Random Forest Results

| Metric | Score |
|--|--|
| R² Score | **0.9558** |
| MAE | **1310.94** |

---

## 🏆 Best Model  

✅ **Random Forest Regressor** performed better than Linear Regression:

- Higher R² Score (**95.58% variance explained**)  
- Lower Mean Absolute Error (**1310.94**)  

This makes Random Forest the better model for car price prediction in this dataset.

---

## 📈 Workflow  

```text
Data Collection
       ↓
Data Cleaning
       ↓
Missing Value Handling
       ↓
Brand Standardization
       ↓
Encoding
       ↓
Scaling
       ↓
Train-Test Split
       ↓
Model Training
       ↓
Model Evaluation
       ↓
Performance Comparison
```

---

## 🚀 Installation  

Clone repository:

```bash
git clone https://github.com/your-username/car-price-prediction.git
cd car-price-prediction
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## 📦 Libraries Used  

```txt
pandas
numpy
matplotlib
seaborn
scikit-learn
jupyter
```





