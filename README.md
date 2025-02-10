**Project 3: Heart Disease Prediction Model (Healthcare - Predictive Analytics)**
📌 Repository Name: Cardio-Disease-Predictor

**Overview**
This project predicts the likelihood of heart disease using patient medical records and demographic data. By leveraging machine learning, the model aids healthcare professionals in early diagnosis and risk assessment.

✅ Completed as part of the Xaltius Data Science Internship
✅ Used 4 ML models, with SVM achieving the highest accuracy (78.47%)
✅ Built an end-to-end pipeline, including data preprocessing, feature selection, and model evaluation

**Dataset**
Source: A subset of Parkway Pantai's healthcare dataset.
Size: 70,000 records, 16 features.
Key Features: Age, Gender, Cholesterol, Blood Pressure, Smoking, Physical Activity.
Target Variable: heart_disease_presence (1 = Disease Present, 0 = No Disease).
Data Exploration & Key Insights
📊 Numeric Feature Distribution: Age, Weight, and Height were clean, but Blood Pressure had significant outliers.
📊 Categorical Feature Imbalance: Fewer smokers and drinkers in the dataset, which may bias predictions.
📊 Strongest Predictors: Cholesterol levels had the highest impact on heart disease risk.

**Machine Learning Models Tested**
Model	Accuracy	F1 Score	Best Performance
Decision Tree	64.58%	0.52	🚫
Logistic Regression	74.21%	0.61	🚫
Random Forest	76.90%	0.68	🚫
SVM	78.47%	0.72	✅
🔹 Best Model: Support Vector Machine (SVM)

**Implementation & Tools**
Programming Language: Python 🐍
Libraries Used: pandas, numpy, matplotlib, seaborn, scikit-learn
EDA & Visualization: matplotlib, seaborn
Feature Engineering: Encoding categorical variables, handling missing values, normalizing continuous variables
Model Training & Evaluation: Confusion matrices, precision-recall tradeoffs
Business Impact
📌 Early identification of high-risk individuals
📌 Data-driven recommendations for heart disease prevention
📌 Integration potential with clinical decision support systems

📄 Presentation: [Project Slides](./Project\ 3\ -\ Healthcare\ -\ Predictive\ Analysis\ -\ Mandisa\ Galetuke.pptx)
📂 Code Notebook: [Heart Disease Prediction.ipynb](./Project\ 3\ -\ Healthcare\ -\ Predictive\ Analytics.ipynb)
