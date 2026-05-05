<h1 align="center">📊 Customer Churn Prediction using Spark MLlib</h1>

<h3 align="center">
Machine Learning Pipeline | PySpark | Spark MLlib | Model Optimization
</h3>

<p align="center"><em>"Predicting customer churn using scalable machine learning pipelines on distributed data."</em></p>

---

## ✨ Overview

This project builds an **end-to-end machine learning pipeline** using **Apache Spark MLlib** to predict customer churn.

It includes data preprocessing, feature engineering, model training, feature selection, and model comparison to identify the best-performing model.

---

## 🚀 Key Features

- 📥 Data preprocessing and cleaning  
- 🔤 Feature engineering and encoding  
- 🤖 Model training using Logistic Regression  
- 📊 Feature selection using Chi-Square test  
- 🔍 Model comparison (LR, Decision Tree, Random Forest, GBT)  
- ⚙️ Hyperparameter tuning using CrossValidator  
- 📈 Evaluation using AUC metric  

---

## 🧠 Tech Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![PySpark](https://img.shields.io/badge/PySpark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Spark MLlib](https://img.shields.io/badge/Spark%20MLlib-FF6F00?style=for-the-badge)

---

## 📂 Project Structure
- customer_churn.csv # Dataset
- customer-churn-analysis.py # ML pipeline
- dataset-generator.py # Synthetic data generator
- model_outputs.txt # Output results


---

## 📊 Dataset Overview

| Feature | Description |
|--------|------------|
| tenure | Months with company |
| MonthlyCharges | Monthly bill |
| TotalCharges | Total billed amount |
| InternetService | Service type |
| PhoneService | Service status |
| Churn | Target variable |

---

## 🔍 ML Pipeline

### 📌 Data Preprocessing
- Handled missing values  
- Encoded categorical features  
- Assembled features into vectors  

---

### 📌 Model Training
- Trained Logistic Regression model  
- Split data into training and testing sets  

---

### 📌 Feature Selection
- Applied **Chi-Square test**  
- Selected most important features  

---

### 📌 Model Comparison
- Evaluated multiple models:
  - Logistic Regression  
  - Decision Tree  
  - Random Forest  
  - Gradient Boosted Trees  

- Best model selected based on **AUC score**

---

## ⚙️ How to Run

```bash
pip install pyspark
```
```bash
spark-submit customer-churn-analysis.py
```
---
### 📌 Project Highlights
- Built a complete ML pipeline using Spark MLlib
- Applied feature engineering and selection techniques
- Performed model comparison and tuning
- Used AUC metric for evaluation
- Processed large-scale data using distributed computing
---
