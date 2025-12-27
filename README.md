# AI_ML_Project
Heart Disease Prediction Using Machine Learning

# Heart Disease Prediction Using Machine Learning

## Overview
This project predicts the likelihood of heart disease in patients using **Python, Data Science, and Machine Learning** techniques.  
It was completed as part of my **6-month AI/ML Engineer Add-On Course at COZMEK**.  
The goal is to analyze patient clinical data and build predictive models to assist in early detection of heart disease.

---

## Problem Statement
Heart disease is one of the leading causes of death worldwide. Early prediction using patient data can help in timely treatment and preventive care.  
This project aims to develop a machine learning model to predict whether a patient has heart disease (target = 1) or not (target = 0) based on clinical features.

---

## Dataset
- **Source:**: Kaggle dataset's 
- **Number of Columns:** 14 features + 1 target  
- **Features Description:**

| Column | Description |
|--------|-------------|
| age    | Age in years |
| sex    | 1 = male, 0 = female |
| cp     | Chest pain type |
| trestbps | Resting blood pressure (mm Hg) |
| chol   | Serum cholesterol in mg/dl |
| fbs    | Fasting blood sugar > 120 mg/dl (1 = true, 0 = false) |
| restecg | Resting electrocardiographic results |
| thalach | Maximum heart rate achieved |
| exang  | Exercise induced angina (1 = yes, 0 = no) |
| oldpeak | ST depression induced by exercise relative to rest |
| slope  | Slope of the peak exercise ST segment |
| ca     | Number of major vessels (0-3) colored by fluoroscopy |
| thal3  | 3 = normal, 6 = fixed defect, 7 = reversible defect |
| target | 1 = heart disease, 0 = no heart disease |



## Tools & Libraries
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn  
- **Environment:** Google Colab  


## Workflow
1. **Data Preprocessing**
   - Handle missing values, encode categorical variables, scale features if necessary  
2. **Exploratory Data Analysis (EDA)**
   - Visualize feature distributions, correlation heatmap, and patterns between features and target  
3. **Feature Selection**
   - Identify most important features influencing heart disease prediction  
4. **Model Building**
   - Train models such as Logistic Regression, Random Forest, Decision Tree, or SVM  
5. **Model Evaluation**
   - Metrics: Accuracy, Precision, Recall, F1-score, Confusion Matrix, ROC-AUC  
6. **Insights & Conclusion**
   - Identify which features strongly affect heart disease prediction  



## Results

- **Key Insights:**  
  Maximum heart rate (`thalach`) and cholesterol (`chol`) are strong indicators of heart disease risk.  
- Include **graphs or charts** from your analysis here for visual impact  



## Future Work
- Hyperparameter tuning to improve model performance  
- Deploy the model using Flask or Streamlit for real-time prediction  
- Incorporate more patient features to increase predictive accuracy  



## Author
**Litteena Babu** – [LinkedIn Profile Link]  
Course: **AI/ML Engineer Add-On Course, COZMEK PVT LTD**



