# Recipe Traffic Prediction for Tasty Bytes

## Overview
This project focuses on predicting recipe traffic for the **Tasty Bytes** website. The primary objective is to develop a model that can accurately forecast which recipes will attract high user traffic, enabling the website to optimize its homepage content and enhance user engagement, ultimately driving subscription growth.

This analysis was conducted as part of the **DataCamp Professional Data Scientist Certification** practical exam.

---

## Table of Contents
- [Project Description](#project-description)
- [Dependencies](#dependencies)
- [Data Information](#data-information)
- [Code Overview](#code-overview)
- [Analysis Summary](#analysis-summary)
- [How to Run the Code](#how-to-run-the-code)
- [Author Information](#author-information)

---

## Project Description
This project aims to predict recipe traffic using machine learning techniques. The workflow includes:

- **Data Cleaning and Preprocessing:** Handling missing values, data type conversions, and encoding categorical variables.
- **Exploratory Data Analysis (EDA):** Visualizing data distributions and relationships to gain insights.
- **Feature Engineering:** Creating new features to improve model predictive performance.
- **Model Development and Evaluation:** Training and evaluating machine learning models (XGBoost and SVM) to predict high-traffic recipes.

Successful implementation of this model can provide actionable insights for content placement on the **Tasty Bytes** homepage, leading to increased user engagement and higher subscription rates.

---

## Dependencies
This project is implemented in **Python 3.x** and requires the following libraries:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
```

It is recommended to use a **Jupyter Notebook environment** (e.g., JupyterLab, Google Colab) to execute the code.

---

## Data Information
The dataset used in this analysis was provided by **Tasty Bytes** and includes:

- **Nutritional details** (calories, carbohydrates, sugar, protein)
- **Recipe category**
- **Serving size**
- **High traffic indicator** (label for prediction)

---

## Code Overview
The primary code for this project is in the Jupyter Notebook:

**`recipe_traffic_prediction_analysis.ipynb`**

This notebook includes all necessary steps such as data loading, preprocessing, exploratory analysis, feature engineering, model training, and evaluation.

---

## Analysis Summary

### **1. Data Cleaning and Preprocessing:**
- Handled missing values and ensured data consistency.
- Encoded categorical variables.

### **2. Exploratory Data Analysis (EDA):**
- Visualized key variables and their relationships.

### **3. Feature Engineering:**
- Created new features to enhance model predictive performance.

### **4. Model Development:**
- Trained **XGBoost** and **SVM** models to predict high-traffic recipes.

### **5. Model Evaluation:**
- Assessed model performance using appropriate evaluation metrics.

---

## How to Run the Code

To execute the analysis, follow these steps:

1. Ensure you have **Python 3.x** installed.
2. Install required libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn xgboost
   ```
3. Open the **`recipe_traffic_prediction_analysis.ipynb`** notebook in a Jupyter environment (JupyterLab or Google Colab).
4. Run all notebook cells sequentially to reproduce the analysis.

---

## Author Information

This project was conducted by **Efstratios Karkanis** as part of the **DataCamp Professional Data Scientist Certification** practical exam.

For any inquiries or collaborations, feel free to reach out!

---

### **License**
This project is licensed under the [MIT License](LICENSE).
