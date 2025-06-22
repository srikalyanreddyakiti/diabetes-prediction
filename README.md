# diabetes-prediction
A Flask-based web app that predicts diabetes using machine learning on the Pima Indians dataset. Built with Python, HTML/CSS, and SVC classifier.

A complete end-to-end machine learning project that predicts the likelihood of diabetes using a dataset of medical parameters. Built using Python, Flask, HTML/CSS, and a trained Support Vector Classifier (SVC) model.

## 🧠 Short Description  
This is a web application for predicting diabetes from user input based on Glucose, Insulin, BMI, and Age using a trained ML model with Flask backend.

## 📁 Project Structure  
├── app.py – Flask web application script  
├── model.py – Model training and saving logic using SVC  
├── diabetes.csv – Dataset used for training (Pima Indians Diabetes Database)  
├── style.css – CSS file for frontend styling  
├── templates/  
│   └── diabetes.html – HTML page for user interaction  

## 📝 Features  
- Cleaned and preprocessed dataset  
- Feature selection based on correlation  
- SVC model training with sklearn  
- Flask web application for prediction  
- HTML + CSS UI with styled form  
- Realtime prediction and result display  

## 🧪 Technologies Used  
- Python  
- pandas, numpy, seaborn, matplotlib  
- scikit-learn (SVC, MinMaxScaler, train_test_split, joblib)  
- Flask (Web Framework)  
- HTML, CSS  

## 📊 Dataset  
Pima Indians Diabetes Database provided by the National Institute of Diabetes and Digestive and Kidney Diseases.

## 🔍 Model Details  
- Algorithm Used: Support Vector Classifier (SVC)  
- Evaluation: Accuracy Score, Confusion Matrix, Classification Report  
- Preprocessing:  
  • Replaced zero values with NaN  
  • Filled missing values  
  • Scaled features using MinMaxScaler  

## 📌 Author  
**Akiti Sri Kalyan Reddy**  
Project originally developed as part of the Data Warehousing and Mining coursework at ICFAI Tech, Hyderabad.
