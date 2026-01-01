# House Price Prediction - Linear Regression

This repository contains the implementation of a Linear Regression model to predict house prices based on square footage, number of bedrooms, and number of bathrooms. This project is part of my data science internship at **Prodigy InfoTech**.

## 📌 Project Overview
The goal of this project is to build a machine learning model that estimates the sale price of houses using a specific subset of features from the dataset.

* **Task:** Implement a linear regression model to predict the prices of houses based on their square footage and the number of bedrooms and bathrooms.
* **Model Used:** Linear Regression (Scikit-Learn).
* **Dataset:** [Kaggle - House Prices: Advanced Regression Techniques](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data).

## 📂 Dataset Details
The model was trained using the `train.csv` file from the Kaggle dataset.
**Selected Features:**
1.  **GrLivArea:** Above grade (ground) living area square feet.
2.  **BedroomAbvGr:** Number of bedrooms above basement level.
3.  **FullBath:** Full bathrooms above grade.
4.  **Target Variable:** SalePrice.

## 🛠️ Technologies Used
* **Python** (Programming Language)
* **Pandas** (Data Manipulation)
* **Matplotlib** (Data Visualization)
* **Scikit-Learn** (Machine Learning)
* **Jupyter Notebook** (Development Environment)

## 🚀 How to Run
1.  Clone this repository.
2.  Install the required libraries:
    ```bash
    pip install pandas scikit-learn matplotlib jupyter
    ```
3.  Download the dataset from Kaggle and place `train.csv` in the project directory.
4.  Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
5.  Run the cells to train the model and view the predictions.

## 📊 Results
The model successfully trained on the dataset and generated predictions.
* **Visualization:** A scatter plot was generated to compare Actual Prices vs. Predicted Prices.
* **Metrics:** Calculated Mean Squared Error (MSE) and R-squared ($R^2$) score to evaluate performance.

---
**Author:** [Nishtha S]
**Internship:** Prodigy InfoTech (Task 01)
