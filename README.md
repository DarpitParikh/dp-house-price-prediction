# 🏡 House Price Prediction System

A machine learning project to predict house prices based on various property features using regression models. Built during the Edunet AI/ML Internship with the aim of solving real-world problems using AI.

## 📌 Project Overview

This project uses housing data to build a predictive model that estimates the price of a house based on features like:
- Square footage
- Location
- Number of bedrooms and bathrooms
- Year built
- Garage size
- Lot area

The main goal is to provide a data-driven, accurate, and automated approach to property valuation, useful for buyers, sellers, and real estate investors.

---

## 🧠 Technologies Used

- **Python** (Programming Language)
- **pandas, numpy** (Data Handling)
- **matplotlib, seaborn** (Visualization)
- **scikit-learn** (Modeling)
- **Streamlit** (Deployment - Optional)
- **Jupyter Notebook** (Development & Experimentation)

---

## ⚙️ Features

- Clean and preprocess housing data
- Train and test multiple regression models
- Evaluate model performance using metrics like R² and RMSE
- Predict house prices for new input data
- Optionally deploy using a web interface

---

## 📁 Project Structure

house-price-prediction/
│
├── data/
│ └── housing.csv # Dataset used
│
├── notebooks/
│ └── house_price_model.ipynb # Main notebook
│
├── app/
│ └── app.py # Streamlit app (optional)
│
├── models/
│ └── trained_model.pkl # Saved model
│
├── README.md # Project overview
└── requirements.txt # Required libraries


---

## 🧪 Model Training

- Models used:
  - Linear Regression
  - Decision Tree
  - Random Forest Regressor (best performer)

- Evaluation Metrics:
  - **R² Score:** ~0.85
  - **RMSE:** ~39,000

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/house-price-prediction.git
cd house-price-prediction

👨‍💻 Contributors
Darpit Parikh
Linkedin(https://www.linkedin.com/in/darpit-parikh-376734313/)

AI/ML Internship - Edunet Foundation | Supported by AICTE & IBM SkillsBuild
