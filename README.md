📝 Heart Disease Dataset - EDA & Data Preparation
📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) and Data Preprocessing on the Heart Disease dataset.
The goal is to clean, analyze, and prepare the data for future Machine Learning tasks such as heart disease prediction.

Through detailed EDA, we identify key patterns, risk factors, and prepare the dataset by handling missing values, feature scaling, and encoding.

📂 Dataset Information
Source: UCI Heart Disease Dataset

Number of Samples: 303

Features:

Age

Sex

Chest Pain Type (cp)

Resting Blood Pressure (trestbps)

Cholesterol (chol)

Fasting Blood Sugar (fbs)

Resting ECG (restecg)

Maximum Heart Rate Achieved (thalach)

Exercise Induced Angina (exang)

ST Depression (oldpeak)

Slope of Peak Exercise ST Segment (slope)

Number of Major Vessels (ca)

Thalassemia (thal)

Target:

1 = Presence of heart disease

0 = No heart disease

📊 Exploratory Data Analysis (EDA)
🔥 Key Insights from the Data:
Age:

People aged 45–60 have the highest risk of heart disease.

Gender:

Males have a higher chance of heart disease than females.

Chest Pain Type:

Asymptomatic chest pain (type 3) is highly associated with heart disease.

Cholesterol:

Higher cholesterol is a risk factor, but not the only factor.

Max Heart Rate (thalach):

People with lower maximum heart rate tend to have heart disease.

Exercise Induced Angina (exang):

Presence of exercise-induced angina significantly increases risk.

ST Depression (oldpeak):

Higher oldpeak values correlate strongly with heart disease.

Slope of ST Segment (slope):

Flat and downsloping ST segments are more common among heart disease patients.

Number of Major Vessels (ca):

More colored vessels imply higher risk of heart disease.

🧹 Data Preprocessing Steps
Handled Missing Values: Dataset had no missing values.

Feature Engineering:

Created age_group and chol_group for better analysis.

Encoding:

Categorical variables already numerical; no additional encoding needed.

Scaling:

Standardized features using StandardScaler to bring them onto a common scale.

🛠 Skills Demonstrated
Data Cleaning

Exploratory Data Analysis (EDA)

Feature Engineering

Data Scaling and Preparation

Visualization with Matplotlib and Seaborn

Deriving actionable insights from data

📈 Visualizations
Correlation Heatmaps

Histograms (Age, Cholesterol)

KDE Plots (Max Heart Rate, ST Depression)

Count Plots (Target distribution, Gender, Chest Pain Type)

Bar Plots (Slope, Fasting Blood Sugar, Number of Vessels)

Pairplots

🚀 Future Scope
Building Machine Learning models like Logistic Regression, Random Forest.

Hyperparameter tuning for model optimization.

Deploying the final predictive model through an API.
