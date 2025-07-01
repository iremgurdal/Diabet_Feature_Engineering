# Diabet_Feature_Engineering
🩺 Diabetes Feature Engineering with Machine Learning
This repository contains a comprehensive feature engineering and data preprocessing workflow on a diabetes dataset. The goal is to build a strong foundation for predictive modeling by exploring and preparing the data efficiently.

📌 Project Objective
To apply systematic feature engineering techniques on a diabetes dataset and build a machine learning-ready data pipeline. This helps improve model performance and gain deeper insights into the variables that impact diabetes risk.

📂 Dataset
The dataset is publicly available on Kaggle and contains medical diagnostic measurements for predicting the presence of diabetes in patients.

Target variable: Outcome (1: Diabetic, 0: Non-Diabetic)

Features: Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age

📎 Source: Kaggle - Diabetes Dataset

🔧 Project Workflow
The project includes the following steps:

Data Exploration (EDA)

Shape, data types, missing values

Outlier detection and handling

Target variable analysis

Feature Engineering

New feature creation (e.g., AgeCategory, BMI_Category)

Feature interactions

Binning and transformations

Encoding & Scaling

One-Hot Encoding for categorical variables

StandardScaler for numerical features

Model Building

Logistic Regression, Random Forest, etc.

Evaluation using accuracy, confusion matrix, precision, recall

📊 Key Techniques Used
pandas, numpy

seaborn, matplotlib

scikit-learn

Feature importance analysis

Pipeline creation

🚀 How to Run
bash
Kopyala
Düzenle
# Clone the repository
git clone https://github.com/yourusername/diabetes-feature-engineering.git

# Navigate into the project directory
cd diabetes-feature-engineering

# Open the Jupyter Notebook
jupyter notebook diabet-feature-engineering.ipynb
📈 Results
The final model achieved an accuracy of ~76%, with improved F1 scores after applying feature engineering techniques.

✍️ Author
İrem Gürdal
Data Scientist / MIS Specialist / Health Information Specialist 
https://www.kaggle.com/code/iremgurdal/diabet-feature-engineering
