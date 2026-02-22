# 📱 Google Play Store Rating Prediction Using Machine Learning

This project aims to predict **application ratings** on the Google Play Store using multiple machine learning regression models. Several models are developed, compared, and improved through model evaluation and optimization to determine the most effective approach for this problem.

---

## 📌 Project Overview

App rating prediction is a regression problem in data science.  
In this project, the workflow includes:

* Data exploration and understanding  
* Data preprocessing and feature engineering  
* Training multiple regression models  
* Model comparison and selection  
* Model improvement for performance optimization  

---

## 📂 Dataset

The project uses a Google Play Store dataset containing both numerical and categorical features.

**Key features include:**

* App category  
* Number of reviews  
* Number of installs  
* Application size  
* Price  
* App type (Free or Paid)  
* Content rating  
* Genre information  

**Target variable:**

* App rating  

---

## ⚙️ Data Preprocessing

The following preprocessing steps are applied:

* Handling missing values  
* Cleaning inconsistent data formats (Installs, Price, Size)  
* Encoding categorical features using one-hot encoding  
* Preparing data for machine learning models  

These steps ensure the dataset is clean, consistent, and suitable for model training.

---

## 🧠 Machine Learning Models

Three regression models are implemented:

### 🔹 Linear Regression

Used as a baseline model to understand the linear relationship between features and app ratings.

### 🔹 Random Forest Regressor

An ensemble model that captures non-linear patterns and interactions between features. While powerful, it may be prone to overfitting.

### 🔹 Gradient Boosting Regressor

An ensemble boosting model that incrementally improves predictions. This model demonstrates strong generalization and benefits from optimization.

---

## 🔧 Model Optimization

Model optimization is applied to improve performance and reduce prediction error.  
This process enhances the model’s ability to generalize to unseen data.

---

## 🏆 Final Model Selection

After comparing all models, the **Gradient Boosting Regressor** is selected as the final model due to its balanced performance and strong generalization capability.

---

## 🚀 How to Run the Project

1. Clone the repository  
2. Install the required dependencies  
3. Run the Jupyter Notebook to reproduce the results  

---

## 📦 Tools & Libraries

* Python  
* pandas  
* numpy  
* matplotlib  
* scikit-learn  

---

## ✨ Future Improvements

* Experiment with advanced boosting models such as XGBoost or LightGBM  
* Improve feature engineering and selection  
* Deploy the model as a web application  
* Add model interpretability techniques  

---

## 👩‍💻 Author

Nikita Amelia Valencia  
Machine Learning & Data Science Enthusiast  

---

## 📜 License

This project is for educational and portfolio purposes.
