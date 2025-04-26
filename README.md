# Heart Disease Dataset - EDA & Data Preparation
# 📌 Project Overview
This project focuses on performing Exploratory Data Analysis (EDA) and Data Preprocessing on the Heart Disease dataset.
The goal is to clean, analyze, and prepare the data for future Machine Learning tasks such as heart disease prediction.

Through detailed EDA, we identify key patterns, risk factors, and prepare the dataset by handling feature scaling and creating feature insights.

# 📂 Dataset Information
Source: UCI Heart Disease Dataset

Number of Samples: 303

# Features:

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

# 📊 Exploratory Data Analysis (EDA)
# 🔥 Key Insights from the Data:
Age: People aged 45–60 have the highest frequency of heart disease cases.

Gender: Males show a higher risk compared to females in this dataset.

Chest Pain Type: Asymptomatic chest pain (type 3) is strongly associated with heart disease.

Cholesterol: Higher cholesterol is observed among patients, but cholesterol alone is not a strong predictor.

Max Heart Rate (thalach): Lower maximum heart rates are associated with heart disease.

Exercise Induced Angina (exang): Presence of angina significantly increases the risk of heart disease.

ST Depression (oldpeak): Higher oldpeak values correlate with heart disease presence.

Slope of ST Segment (slope): Flat and downsloping ST segments are indicators of heart disease.

Number of Major Vessels (ca): More colored vessels seen in fluoroscopy indicate higher risk.

# 🧹 Data Preprocessing Steps
Handled Missing Values: Dataset had no missing values.

Feature Engineering:

Created age_group and chol_group for improved EDA.

Feature Scaling:

Applied StandardScaler to numerical features for ML-readiness.

# 🛠 Skills Demonstrated
Data Cleaning

Exploratory Data Analysis (EDA)

Feature Engineering

Data Scaling and Normalization

Visualization using Matplotlib and Seaborn

Deriving actionable insights from raw data

# 📈 Visualizations
Correlation Heatmaps

Histograms (Age, Cholesterol)

KDE Plots (Max Heart Rate, ST Depression)

Count Plots (Target distribution, Gender, Chest Pain Type)

Bar Plots (Slope, Fasting Blood Sugar, Number of Vessels)

Pairplots

# 🚀 Future Scope
Build Machine Learning models such as Logistic Regression, Random Forest.

Perform hyperparameter tuning for model optimization.

Deployment of predictive models using APIs.
