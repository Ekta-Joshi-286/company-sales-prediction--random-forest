# Company Sales High Prediction – Random Forest

## 📌 Project Overview
This project aims to identify the **key factors that drive high sales** using a **Random Forest classification model**.  
The Sales variable is converted into categorical levels and predicted using multiple store-level attributes.

This analysis helps businesses understand which factors contribute most to increased sales performance.

---

## 🎯 Problem Statement
A cloth manufacturing company wants to understand which attributes or segments lead to **high sales**.

Approach:
- Convert **Sales** into a categorical variable
- Use all other variables as independent features
- Build a **Random Forest classification model**
- Analyze feature importance to identify sales drivers

---

## 📊 Dataset Description
The dataset contains around **400 records** with the following variables:

- **Sales** – Unit sales (in thousands)
- **Competitor Price** – Price charged by competitors
- **Income** – Community income level
- **Advertising** – Local advertising budget
- **Population** – Population size
- **Price** – Company product price
- **Shelf Location** – Shelf quality (Bad, Medium, Good)
- **Age** – Average age of population
- **Education** – Education level
- **Urban** – Urban or rural location
- **US** – Store located in the US or not

---

## 🔍 Exploratory Data Analysis (EDA)
EDA was performed to understand data distribution and relationships:
- Checked data types, missing values, and summary statistics
- Analyzed Sales distribution
- Converted Sales into categorical levels (Low, Medium, High)
- Visualized relationships between Sales and key features

---

## ⚙️ Data Preprocessing
- Converted Sales into categorical target variable
- Removed original Sales column after categorization
- Encoded categorical variables using one-hot encoding
- Split data into training and testing sets

---

## 🤖 Model Building
- Algorithm Used: **Random Forest Classifier**
- Ensemble of decision trees to improve prediction accuracy
- Model trained on training dataset

---

## 📈 Model Evaluation
The model was evaluated using:
- Accuracy Score
- Confusion Matrix
- Classification Report

These metrics help assess how well the model predicts **high sales**.

---

## 🌟 Feature Importance
Feature importance analysis was performed to identify the most influential factors.  
Key contributors to high sales include:
- Price
- Advertising
- Income
- Shelf Location

---


---

## 🛠 Tools & Technologies Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- Jupyter Notebook

---

## ✅ Conclusion
The Random Forest model successfully identified the major factors influencing high sales.  
These insights can help the company optimize pricing, advertising strategies, and shelf placement to improve overall sales performance.

---

## 📌 Author
Ekta Joshi

