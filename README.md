# Heart Disease Prediction App ❤️

A machine learning–based web application that predicts the likelihood of heart disease using patient medical attributes.  
The application provides instant predictions through an interactive Streamlit interface.

---

## Overview

Early detection of heart disease plays a critical role in preventing severe health complications.  
This project uses a trained machine learning classification model to assist in predicting the presence of heart disease based on commonly used clinical parameters.

The system is designed as a lightweight and easy-to-use web application suitable for demonstrations and educational purposes.

---

## Problem Statement

Heart disease diagnosis often requires interpreting multiple medical parameters simultaneously.  
Manual analysis can be time-consuming and prone to error, especially in early-stage detection.

This project aims to leverage machine learning to provide fast and consistent predictions based on patient data.

---

## Solution Approach

- A supervised machine learning classification model is trained on structured medical data.
- Key health features such as age, cholesterol level, heart rate, and ECG results are used.
- The trained model is saved using `joblib`.
- A Streamlit-based web interface allows users to input medical data and receive real-time predictions.

---

## Features

- Interactive medical data input
- Real-time heart disease prediction
- Clean and user-friendly interface
- Lightweight deployment using Streamlit
- Pre-trained model for fast inference

---

## Tech Stack

- **Python**
- **NumPy**
- **Scikit-learn**
- **Streamlit**
- **Joblib**

---

## Project Structure
heart-disease-prediction/

│
├── app.py # Streamlit application

├── final_model.pkl # Trained machine learning model

├── requirements.txt # Project dependencies

├──01
├──02
├──03
├──04
├──05
├──06



---

## Input Features

- Age
- Sex
- Chest Pain Type (cp)
- Resting Blood Pressure (trestbps)
- Cholesterol (chol)
- Fasting Blood Sugar (fbs)
- Resting ECG (restecg)
- Maximum Heart Rate Achieved (thalch)
- Exercise Induced Angina (exang)
- ST Depression (oldpeak)
- Slope of ST Segment (slope)
- Thalassemia (thal)

---

## Output

- **Heart Disease Detected**
- **No Heart Disease Detected**

---

## How to Run the Project

1. Clone the repository:
```bash
git clone https://github.com/your-username/heart-disease-prediction.git
cd heart-disease-prediction

1.Install dependencies:

pip install -r requirements.txt

2.run the notebook by the sequence
python run 01_data_preprocessing.ipynb
python run 02  ....

3.Run the Streamlit app:

streamlit run app.py
```

## Future Improvements

Display prediction probability

Add feature importance visualization

Improve UI with risk indicators

Deploy the app on Streamlit Cloud

Support batch predictions

## Disclaimer

This application is intended for educational and demonstration purposes only and should not be used as a medical diagnostic tool.

## Author

Mohamed Gamal

Machine Learning & AI Engineer
