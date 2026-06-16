# ❤️ Heart Stroke Disease Prediction

A Machine Learning-powered web application built with **Streamlit** that predicts the likelihood of heart disease based on patient health parameters.

## 🚀 Live Demo

**Try the app here:**

https://kakul23fe10cse00261-heart-stroke-disease-prediction-app-j4tdmj.streamlit.app/

---

## 📌 Project Overview

This project uses a trained **Logistic Regression** model to predict whether a person is at risk of heart disease based on medical attributes such as:

* Age
* Sex
* Chest Pain Type
* Resting Blood Pressure
* Cholesterol Level
* Fasting Blood Sugar
* Resting ECG Results
* Maximum Heart Rate
* Exercise-Induced Angina
* OldPeak (ST Depression)
* ST Slope

The application provides an easy-to-use interface where users can enter their health information and receive an instant prediction.

---

## 🛠️ Technologies Used

* Python
* Streamlit
* Pandas
* NumPy
* Scikit-learn
* Joblib

---

## 📂 Project Structure

```text
Heart-Stroke-Disease-Prediction/
│
├── app.py                         # Streamlit application
├── heart.ipynb                    # Model training notebook
├── heart.csv                      # Dataset
├── Logistic_regression_heart.pkl  # Trained ML model
├── scaler.pkl                     # Feature scaler
├── columns.pkl                    # Encoded feature columns
├── requirements.txt               # Dependencies
└── README.md
```

---

## 🤖 Machine Learning Workflow

1. Data Collection
2. Data Preprocessing
3. One-Hot Encoding of Categorical Features
4. Feature Scaling
5. Model Training using Logistic Regression
6. Model Evaluation
7. Model Serialization using Joblib
8. Deployment using Streamlit Cloud

---

## 📊 Input Features

| Feature        | Description                       |
| -------------- | --------------------------------- |
| Age            | Patient age                       |
| Sex            | Male / Female                     |
| ChestPainType  | ATA, NAP, TA, ASY                 |
| RestingBP      | Resting blood pressure            |
| Cholesterol    | Serum cholesterol                 |
| FastingBS      | Fasting blood sugar > 120 mg/dL   |
| RestingECG     | ECG results                       |
| MaxHR          | Maximum heart rate achieved       |
| ExerciseAngina | Exercise-induced angina           |
| Oldpeak        | ST depression value               |
| ST_Slope       | Slope of peak exercise ST segment |

---

## ▶️ Running Locally

### Clone the repository

```bash
git clone https://github.com/KAKUL23FE10CSE00261/Heart-Stroke-Disease-Prediction.git
cd Heart-Stroke-Disease-Prediction
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the Streamlit app

```bash
streamlit run app.py
```

---

## 📈 Prediction Output

The model predicts:

* ✅ Low Risk of Heart Disease
* ⚠️ High Risk of Heart Disease

---

## ⚠️ Disclaimer

This application is intended for educational and research purposes only. It is not a substitute for professional medical diagnosis, treatment, or advice. Always consult qualified healthcare professionals for medical decisions.

---

## 👨‍💻 Author

**Kakul Barsiya**

Manipal University Jaipur

GitHub: https://github.com/KAKUL23FE10CSE00261

---

## ⭐ Future Improvements

* Probability score for predictions
* Interactive visualizations
* Multiple model comparison
* Model explainability using SHAP
* Better UI/UX design
* Cloud deployment enhancements

```
```
