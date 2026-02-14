# Heart_Disease-Classification
🏥 Disease Prediction using Machine Learning
📌 Project Overview

This project predicts the possibility of a disease based on patient medical data using Machine Learning classification algorithms.
It compares multiple models and selects the best one based on accuracy.

The system uses features like age, medical test results, and other health indicators to predict whether a patient is likely to have a disease.

🎯 Objective

To build a machine learning model that can:

Analyze structured medical data

Compare different classification algorithms

Predict disease presence accurately

🧠 Algorithms Used

The following models were trained and compared:

Logistic Regression

Support Vector Machine (SVM)

Random Forest

📊 Model Performance
Model	Accuracy
Logistic Regression	82%
SVM	89%
Random Forest	100%

Random Forest performed the best and was selected as the final model.

📁 Dataset Features

The dataset contains medical attributes such as:

Age

Sex

Blood pressure

Cholesterol

Heart rate

Other clinical measurements

Target column:

0 → No disease

1 → Disease present

⚙️ Project Workflow

Data Loading

Data Preprocessing

Feature & Target Separation

Train–Test Split (80/20)

Feature Scaling using StandardScaler

Model Training

Accuracy Comparison

Feature Importance Visualization

Model Saving using Pickle

📦 Libraries Used

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Pickle

🚀 How to Run
1️⃣ Clone the repository
git clone https://github.com/your-username/disease-prediction-ml.git
cd disease-prediction-ml

2️⃣ Install dependencies
pip install pandas numpy scikit-learn matplotlib

3️⃣ Run the notebook/script

Open and run:

disease_prediction.ipynb
