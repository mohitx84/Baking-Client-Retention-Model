# Baking-Client-Retention

This project focuses on building and evaluating multiple machine learning models to predict customer churn. The goal is to identify customers who are likely to leave a service, enabling businesses to take proactive retention measures.

## 📌 Objective
To compare the performance of various classification algorithms in predicting customer churn and identify the most effective model based on accuracy, precision, and recall metrics.

## 🧠 Machine Learning Models Used
- Logistic Regression  
- K-Nearest Neighbors (KNN)  
- Decision Tree Classifier  
- Random Forest Classifier  
- XGBoost Classifier  
- CatBoost Classifier  

## 🧪 Data Preprocessing
- Outlier detection using boxplots  
- Feature scaling using `StandardScaler`  
- Addressed class imbalance using **SMOTE (Synthetic Minority Oversampling Technique)**  

## 🧾 Evaluation Metrics
- Accuracy  
- Precision  
- Recall  
- F1-Score  
- Confusion Matrix  
- Classification Report  

## ✅ Key Results
- **XGBoostClassifier** achieved the **highest performance**, with an **accuracy of 85%** and the best overall precision.
- Ensemble models such as Random Forest and CatBoost also performed well in terms of recall.

## 📊 Visualization
- Boxplots for outlier detection  
- Bar plots for model comparison (accuracy, precision, recall)

