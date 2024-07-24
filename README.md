# Regression Project: Rental Prices for Units Across Canada (2024)

### Project Overview

This project aims to analyze and predict rental prices for residential units across Canada in 2024. Utilizing a dataset sourced from rentfaster.ca, the project explores the factors influencing rental prices and employs multiple regression models to achieve accurate predictions.

### Description

In 2024, rental prices in Canada show significant variation driven by factors such as location, property type, and the number of bedrooms. Major urban centers like Toronto and Vancouver command higher rents due to elevated demand and limited supply, with one-bedroom apartments averaging between $1,800 and $2,500. Conversely, smaller cities and rural areas present more affordable options.

  - Exploratory Data Analysis (EDA)
  - Data Cleaning and Preparation
  - Feature Engineering
  - Model Comparison and Validation
  - Predictions using the final model

### Objectives

  - Load and Inspect Data: Understand the dataset structure and contents. The dataset is loaded into a Pandas DataFrame,        and the initial structure and contents of the data are examined.
  - Exploratory Data Analysis (EDA): The dataset is thoroughly explored to understand the relationships between the features and the target variable (rental price). This includes analyzing the distribution of variables, identifying missing values, and examining the correlations between different features.
  - Data Cleaning and Preparation: The dataset is cleaned and preprocessed, including handling missing values, converting data types, and encoding categorical variables as needed.
  - Model Development: Multiple regression models, such as Linear Regression, Lasso Regression, and Ridge Regression, are developed and compared to find the one that predicts rental prices most accurately.
  - Model Evaluation: The selected model is validated using techniques like cross-validation and tested on a held-out test set to evaluate its performance.
  - Prediction: The final, best-performing model is used to make predictions on new, unseen data, and the results are analyzed and interpreted.

### Dataset

The dataset contains various features, including:

  - rentfaster_id
  - city
  - province
  - address
  - price
  - beds
  - baths
  - sq_feet
  - furnishing
  - availability_date
  - pet_policy (e.g., smoking, cats, dogs)

### Tools and Libraries

The following libraries are used in this project:

  - pandas for data manipulation
  - numpy for numerical operations
  - scikit-learn for machine learning models
  - matplotlib and seaborn for data visualization
    
You can install these packages using pip:

pip install pandas numpy matplotlib seaborn ...

### Getting Started
  1. Clone the Repository: git clone https://github.com/Waliid18/Regression_Project
  2. Run the Jupyter Notebook: Launch the notebook to explore the analysis and predictions:
     jupyter notebook Regression_Project_1.ipynb
### Summary
This project provides a comprehensive analysis of rental prices across Canada in 2024 and the development of predictive models to estimate these prices based on various features. The insights gained from this study can be valuable for various stakeholders, such as real estate investors, policymakers, and renters, in understanding the factors that influence rental prices and making informed decisions.

The project showcases the application of data science techniques, including data exploration, feature engineering, model selection, and model evaluation, to solve a real-world problem in the residential rental market. The results of this project can be used to inform decision-making, guide policy interventions, and contribute to a better understanding of the dynamics shaping the Canadian rental landscape.
