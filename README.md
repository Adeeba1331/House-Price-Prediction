# House Price Prediction Using Machine Learning

#Project Overview

This project focuses on predicting **house prices** using the **California Housing Dataset**. I implemented three models: Linear Regression, Decision Tree Regressor, and Random Forest Regressor, to compare their performance and select the best model.

This is a beginner-friendly project designed to demonstrate an **end-to-end machine learning workflow**.

---

## Problem Statement

Predict house prices based on features like median income, house age, average rooms, population, and location coordinates.

---

## Dataset

* **Source:** California Housing Dataset (sklearn.datasets)
* **Features:** MedInc, HouseAge, AveRooms, AveBedrms, Population, AveOccup, Latitude, Longitude
* **Target:** MedHouseVal (Median House Value)

---

## Tools & Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib / Seaborn
* Scikit-learn
* Jupyter Notebook

---

## Methodology

1. **Load Dataset & Data Inspection**

   * Loaded dataset using `sklearn.datasets.fetch_california_housing`
   * Checked data shape, missing values, and summary statistics

2. **Exploratory Data Analysis (EDA)**

   * Visualized correlations using a heatmap
   * Identified median income (MedInc) as the most influential feature

3. **Feature & Target Separation**

   * `X` contains input features
   * `y` contains target variable (MedHouseVal)

4. **Train-Test Split**

   * Split dataset into 80% training and 20% testing using `train_test_split`

5. **Model Training & Prediction**

   * Built **Linear Regression** model (R² = 0.57)
   * Built **Decision Tree Regressor** (R² = 0.62)
   * Built **Random Forest Regressor** (R² = 0.80)

6. **Model Evaluation**

   * Evaluated models using **R² score** and **RMSE**
   * Compared model performances to select the best one

---

## Model Performance

| Model             | R² Score | Notes                                     |
| ----------------- | -------- | ----------------------------------------- |
| Linear Regression | 0.57     | Baseline model                            |
| Decision Tree     | 0.62     | Improved by capturing non-linear patterns |
| Random Forest     | 0.80 ✅   | Best performance, ensemble method         |

---

## Key Learnings

* Feature-target separation and train-test split
* Exploratory data analysis and correlation analysis
* Implemented and compared Linear Regression, Decision Tree, and Random Forest
* Evaluated models using R² score and RMSE
* Ensemble learning significantly improved performance

---

## How to Run the Project

1. Clone the repository
2. Install required libraries:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```
3. Open the Jupyter Notebook
4. Run all cells step by step

---

## Conclusion

This project helped me gain hands-on experience in **regression modeling and ensemble methods**.
Random Forest proved to be the most effective, achieving an **R² score of 0.80**, demonstrating the importance of using advanced models for real-world datasets.

---

*If you find this project useful, feel free to star the repository!*

---
> #DataScience #MachineLearning #Python #RandomForest #Regression

