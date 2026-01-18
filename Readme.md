# Project 4 – Titanic Survival Prediction System

## Project Overview

You are required to develop a **Titanic Survival Prediction System** using a machine learning algorithm. The system predicts whether a passenger survived the Titanic disaster based on selected features from the *Titanic: Machine Learning from Disaster* dataset.

The dataset contains multiple passenger attributes; however, for this project, only the following features may be used:

- Pclass  
- Sex  
- Age  
- SibSp  
- Parch  
- Fare  
- Embarked  
- Survived (target variable)

> 👉 To build the predictive model, select any five (5) input features from the recommended list above (excluding **Survived**, which is the output feature or target variable).

---

## PART A — Model Development

**File:** `model_development.py` or `model_building.ipynb`

You are required to:

- Load the Titanic dataset.  
- Perform data preprocessing, including:  
  - Handling missing values  
  - Feature selection  
  - Encoding categorical variables (e.g., Sex, Embarked)  
  - Feature scaling (where required)  

- Implement any one of the following machine learning algorithms:  
  - Logistic Regression  
  - Random Forest Classifier  
  - Support Vector Machine (SVM)  
  - K-Nearest Neighbours (KNN)  

- Train the model using the dataset.  
- Evaluate the model by printing a classification report.  
- Save the trained model to disk using an appropriate method (e.g., Joblib or Pickle).  
- Demonstrate that the saved model can be reloaded and used for prediction without retraining.

---

## PART B — Web GUI Application

**Files:** `app.py` and `index.html` (if applicable)

Develop a simple Web-based Graphical User Interface (GUI) that:

- Loads the saved trained classification model  
- Allows users to input passenger details  
- Passes the input data to the model  
- Displays the survival prediction result (*Survived / Did Not Survive*)

---

## Permitted Technologies / Stack

- Flask + HTML/CSS  
- Streamlit  
- FastAPI  
- Django (not recommended)  
- Gradio  

---

## PART C — GitHub Submission

Upload the entire project to GitHub using the structure below:

/Titanic_Project_yourName_matricNo/
|
|- app.py
|- requirements.txt
|
|- /model/
| |- model_building.ipynb
| |- titanic_survival_model.pkl
|
|- /static/
| |- style.css (optional, if applicable)
|
|- /templates/
|- index.html (if applicable)

---

## PART D — Deployment Instructions

Deploy the Web GUI using any one of the following platforms:

- Render.com  
- PythonAnywhere.com  
- Streamlit Cloud  
- Vercel  