# 🩺 Diabetes Prediction Web App

This is a Machine Learning-powered web application built using **Streamlit** that predicts whether a person is likely to have diabetes based on medical information.

![App Screenshot](https://via.placeholder.com/800x400?text=Add+a+screenshot+here)

---

## 🚀 Live Demo

[Click here to try the app on Streamlit Cloud](#) <!-- (replace with actual link once deployed) -->

---

## 🔍 Features

- Input features: Pregnancies, Glucose, Blood Pressure, Skin Thickness, Insulin, BMI, Diabetes Pedigree Function, Age
- Predicts diabetes risk using a pre-trained model
- Clean and simple web interface using Streamlit

---

## 🧠 Model Info

- Trained using the **Pima Indians Diabetes Dataset**
- Classification algorithm used: `RandomForestClassifier` / `LogisticRegression` *(customize this based on your model)*
- Evaluation metric: Accuracy

---

## 📁 Project Structure

```plaintext
.
├── diabetes_Prediction_web_app.py      # Streamlit app script
├── trained_model.sav                   # Saved ML model
├── requirements.txt                    # Python dependencies
└── README.md                           # This file
🛠️ Installation
To run the app locally:

git clone https://github.com/<your-username>/diabetes-prediction-app.git
cd diabetes-prediction-app
pip install -r requirements.txt
streamlit run diabetes_Prediction_web_app.py
📦 Dependencies
streamlit

scikit-learn

pandas

numpy

pickle

📌 Author
Devendra Kumar Mahto
LinkedIn • GitHub

📜 License
This project is licensed under the MIT License.

🌐 Deployment (Streamlit Cloud)
To deploy this app:

Push your code to a public GitHub repo.

Go to https://streamlit.io/cloud.

Click “Deploy an app” and connect your GitHub repo.

Set the main file path: diabetes_Prediction_web_app.py

Click Deploy.

