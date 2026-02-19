# DevelopersHub AI/ML Engineering Internship Tasks
## Task 3: Heart Disease Prediction

### Task Objective
Build a machine learning model to predict whether a person is at risk of heart disease based on medical attributes.

### Dataset Used
- **Source:** UCI Heart Disease Dataset (Kaggle Version)  
- **Features Used:** Age, Sex, Chest Pain Type, Resting Blood Pressure, Cholesterol, Fasting Blood Sugar, Resting ECG, Maximum Heart Rate, ST Depression, Number of Major Vessels, Thalassemia, and others  
- **Target Variable:** Presence of Heart Disease (0 = No Disease, 1 = Disease)

### Models Applied
- Logistic Regression  
- Random Forest Classifier  

### Evaluation Metrics
- Accuracy  
- Confusion Matrix  
- ROC Curve  
- AUC Score  

### Key Results and Findings
- Random Forest typically performs better than Logistic Regression.  
- Higher AUC score indicates better ability to distinguish between classes.  
- Important predictors include chest pain type (cp), maximum heart rate (thalach), ST depression (oldpeak), number of major vessels (ca), and thalassemia (thal).  
- Patients with higher chest pain severity and abnormal ECG readings are more likely to have heart disease.  
- Machine learning models can effectively predict heart disease risk using clinical features.  
- Random Forest showed better performance and feature interpretability.  

### Notebook: https://colab.research.google.com/drive/114beSbeprv4_XT316eQMYdCLHcEJPJSh?usp=sharing
