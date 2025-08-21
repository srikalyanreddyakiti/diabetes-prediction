# diabetes-prediction

A Flask-based web application that predicts the likelihood of diabetes using a machine learning model trained on the Pima Indians Diabetes Dataset. The project combines Python, Flask, HTML/CSS, and a Support Vector Classifier (SVC) to deliver real-time predictions through a simple web interface.

---

## Project Structure

```
.
├── app.py              # Flask web application
├── model.py            # Model training and saving logic (SVC)
├── diabetes.csv        # Dataset used for training (Pima Indians Diabetes Database)
├── style.css           # CSS file for frontend styling
├── templates/
│   └── diabetes.html   # HTML page for user interaction
```

---

## Features

- Data cleaning and preprocessing  
- Feature selection based on correlation  
- SVC model training with scikit-learn  
- Flask backend for real-time predictions  
- HTML + CSS frontend with interactive form  
- Results displayed directly to the user  

---

## Technologies Used

- Python  
- pandas, numpy, seaborn, matplotlib  
- scikit-learn (SVC, MinMaxScaler, train_test_split, joblib)  
- Flask (web framework)  
- HTML, CSS  

---

## Dataset

The project uses the **Pima Indians Diabetes Database**, provided by the National Institute of Diabetes and Digestive and Kidney Diseases.

---

## Model Details

- **Algorithm**: Support Vector Classifier (SVC)  
- **Evaluation**: Accuracy score, confusion matrix, classification report  
- **Preprocessing Steps**:  
  - Replaced zero values with NaN  
  - Filled missing values  
  - Applied MinMaxScaler for feature scaling  

---

## Author

**Sri Kalyan Reddy Akiti**  
Data Science and Artificial Intelligence  
