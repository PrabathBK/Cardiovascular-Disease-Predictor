# Cardiovascular-Disease-Predictor
Cardiovascular Disease Classification Project

🔍 Overview:
This project focuses on predicting the presence or absence of cardiovascular disease based on various health metrics. Using a Kaggle dataset, we explore the data, perform feature engineering, handle outliers, and apply machine learning algorithms for classification.

Key Features:
Data Exploration: Initial analysis to understand the dataset's structure and distribution.
Feature Engineering: Created new features such as Body Mass Index (BMI) and performed age normalization.
Data Cleaning: Removed outliers using the Interquartile Range (IQR) method.
Modeling: Employed a Voting Classifier combining KNN, Logistic Regression, SVM, and Random Forest algorithms.
Evaluation: Achieved a high accuracy score and performed a comprehensive classification report.

Dataset:
Source: Kaggle
Size: 70,000 records initially, reduced to 62,745 after data cleaning
Attributes: Age, gender, blood pressure (systolic and diastolic), cholesterol level, glucose level, smoking and alcohol habits, physical activity level, and cardiovascular disease status.

Technologies Used:
Programming Language: Python
Libraries: Pandas, NumPy, Seaborn, Matplotlib, Scikit-learn
Tools: Jupyter Notebook, Kaggle Docker Image

Results:
Achieved 100% accuracy on the test dataset using the Voting Classifier.
Provided insights into key factors contributing to cardiovascular disease.
Demonstrated the importance of data preprocessing and feature engineering in improving model performance.
