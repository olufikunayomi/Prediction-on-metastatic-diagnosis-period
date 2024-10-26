# Prediction-on-metastatic-diagnosis-period
The dataset includes around 19,000 records of patients with metastatic triple-negative breast cancer, featuring demographics, health info, socioeconomic indicators, and climate data. The goal is to predict the Metastatic Diagnosis Period (in days) for each patient in the test set, enhancing understanding of factors influencing cancer progression.

Aim:
The primary aim of this project was to predict the 'metastatic_diagnosis_period' for patients diagnosed with metastatic triple-negative breast cancer, utilizing various patient characteristics and demographic data. The goal was to provide insights that could potentially assist in treatment planning and improving patient outcomes.

Scope:
The project involved analyzing a dataset with approximately 19,000 records, which was divided into training and test sets. The dataset included diverse features such as patient demographics (age, race, and gender), diagnosis codes, treatment information, and socio-economic data derived from zip codes. Special attention was given to cleaning and preprocessing the data, including handling missing values and dropping irrelevant columns.

Solution:
To tackle the prediction task, various data science techniques were employed, including the use of libraries such as NumPy, Pandas, Scikit-learn, Seaborn, and Matplotlib. The following steps were taken:

Data Cleaning: Missing values were imputed, particularly in the BMI and payer type columns, while irrelevant features were removed.
Exploratory Data Analysis (EDA): Visualizations were created to understand the distribution and relationships within the data, separating categorical and numerical features.
Modeling: Several algorithms were applied, including Linear Regression, Ridge Regression, Random Forest, and the use of Simple Imputer for missing value handling. The model's performance was evaluated using Root Mean Squared Error (RMSE), and the best-performing model was selected for predictions.




