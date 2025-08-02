# Heart_Disease_Prediction

📌 Project Goal
Develop a binary classification model to predict the presence of heart disease using patient vitals and health metrics.
🛠 Tools & Technologies
- Python
- Pandas & NumPy
- Scikit-learn (Logistic Regression)
- Matplotlib & Seaborn (for visualization)
📂 Dataset

Dataset: UCI Heart Disease Dataset
URL: https://archive.ics.uci.edu/ml/datasets/heart+Disease

Features include:
- Age
- Sex
- Chest Pain Type
- Resting Blood Pressure
- Cholesterol
- Fasting Blood Sugar
- Rest ECG
- Max Heart Rate Achieved
- Exercise Induced Angina
- Oldpeak (ST depression)
- Slope of ST
- Number of major vessels
- Thalassemia

🔍 Model

1. Data Cleaning & Preprocessing (handle nulls, encode categories)
2. Feature selection and standardization
3. Train/test split
4. Apply Logistic Regression
5. Evaluate model using accuracy, precision, recall, and ROC curve

🚀 How to Run

1. Install dependencies:
   pip install pandas numpy matplotlib seaborn scikit-learn
2. Load the dataset
3. Run preprocessing script
4. Train logistic regression model
5. Visualize evaluation metrics

📈 Applications

- Early detection of cardiovascular risk
- Support for clinical decision-making
- Health monitoring applications

📎 Optional Improvements

- Use ensemble models (Random Forest, XGBoost)

Logistic Regression Model Evaluation Metrics:
<img width="567" height="435" alt="Logistic Regression Model Evaluation Metrics" src="https://github.com/user-attachments/assets/6f481a8d-3bb6-4412-bae4-95e9aeecd3a2" />

- Apply feature engineering
- Deploy the model with a Flask API or Streamlit app
