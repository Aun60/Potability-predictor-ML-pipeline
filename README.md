# Potability Predictor: A Machine Learning Pipeline

This project builds a comprehensive machine learning pipeline to predict water potability using the **Water Potability Dataset**. It explores various classification models, balances the dataset, performs extensive preprocessing, and compares model performance using key evaluation metrics and visualizations.

---

## 📂 Dataset
- **Source**: [Water Potability Dataset](https://www.kaggle.com/datasets/adityakadiwal/water-potability)
- **Target Variable**: `Potability` (0 = Not safe to drink, 1 = Safe to drink)

---

## 🔧 Pipeline Overview

### 1. Preprocessing
- **Missing Value Imputation**
- **Class Imbalance Handling** using `RandomUnderSampler`
- **Outlier Detection** using boxplots
- **Feature Scaling** using `StandardScaler`
- **Encoding** if needed (handled internally by pipeline)

### 2. Exploratory Data Analysis (EDA)
- Pairplots, Boxplots, Countplots
- Summary statistics
- Correlation analysis

### 3. Models Trained
- Logistic Regression
- K-Nearest Neighbors (KNN)
- Decision Tree
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- AdaBoost
- Bagging Classifier
- Voting Ensemble Classifier

### 4. Evaluation Metrics
- **Confusion Matrix**
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **ROC Curve & AUC**

### 5. Hyperparameter Tuning
- Performed using `GridSearchCV` on various models for optimal performance

---

## 📊 Visualizations
- Class distribution before and after undersampling
- Outlier boxplots
- Pairplot for feature relationships
- ROC Curves per model
- Confusion Matrices

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/potability-predictor-ml-pipeline.git
   cd potability-predictor-ml-pipeline
