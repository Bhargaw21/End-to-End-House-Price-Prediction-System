# Data-Driven Property Price Prediction System

## 📌 Overview
This project implements an end-to-end machine learning pipeline to predict residential property prices using historical housing data.  
It covers the complete ML lifecycle including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and deployment readiness.

The goal is to help users estimate fair property prices based on multiple housing attributes and market indicators.

---

## 🎯 Project Objectives
- Analyze real estate data to identify key factors influencing property prices  
- Build and evaluate machine learning models for accurate price prediction  
- Perform feature engineering and normalization to improve model performance  
- Deploy the trained model using a REST-based interface  

---

## 🛠 Tech Stack

**Programming & Machine Learning**
- Python
- Pandas, NumPy
- Scikit-learn

**Visualization & Analysis**
- Matplotlib
- Seaborn
- Jupyter Notebook

**Backend & Deployment**
- Flask (REST API)
- Docker

**Data & Version Control**
- SQL
- Git & GitHub

---

## 📂 Dataset
- Source: Kaggle (Beijing Housing Dataset – Lianjia)
- Size: ~318,000 rows and 26 features
- Includes property size, location, number of rooms, renovation condition, construction year, and pricing details

> Note: Dataset files are excluded from the repository using `.gitignore`.  
> The dataset source is provided for reproducibility.

---

## 🔄 Project Workflow
1. Data Collection  
2. Exploratory Data Analysis (EDA)  
3. Data Cleaning and Preprocessing  
4. Feature Engineering and Selection  
5. Model Training and Evaluation  
6. Hyperparameter Tuning  
7. Model Deployment Preparation  

---

## 📊 Exploratory Data Analysis (EDA)
- Analyzed feature distributions and correlations  
- Handled missing and inconsistent values  
- Identified important predictors such as property size, number of rooms, renovation condition, and community averages  
- Detected and treated outliers using IQR-based techniques  

---

## 🧩 Feature Engineering
- Removed irrelevant and redundant features  
- Encoded categorical variables  
- Normalized numerical features using Min-Max scaling  
- Selected top features contributing most to price prediction  

---

## 🤖 Model Development

**Models Evaluated**
- Linear Regression  
- K-Nearest Neighbors  
- Decision Tree Regressor  
- Random Forest Regressor  

**Final Model**
- Random Forest Regressor  
- Selected based on performance and generalization ability  

---

## 📈 Model Performance
- Training Accuracy: ~94%  
- Testing Accuracy: ~90%  

Performance was evaluated using standard regression metrics to ensure reliability.

---

## 🚀 Deployment
- Integrated the trained model with a Flask-based REST API  
- Created a simple user interface for price prediction  
- Containerized the application using Docker for portability  

---

## 💡 Key Learnings
- Designing end-to-end ML pipelines  
- Importance of EDA and feature engineering  
- Model selection and evaluation trade-offs  
- Basics of ML deployment and API integration  

---

## ⚠ Limitations & Future Improvements
- Model size can be optimized further  
- Support for additional regional datasets  
- Experimentation with advanced models and ensembling  
- Cloud-based deployment and monitoring  

---

## 📁 Repository Structure

---

## ▶️ How to Run Locally

```bash
git clone https://github.com/Bhargaw21/End-to-End-House-Price-Prediction-System.git
cd End-to-End-House-Price-Prediction-System
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app/app.py


👤 Author

Bhargaw Kumar Singh
GitHub: https://github.com/Bhargaw21
