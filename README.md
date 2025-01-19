# NIRF Rank Predictor

The **NIRF Rank Predictor** is a machine learning project designed to predict the NIRF rankings of engineering colleges based on historical data and relevant ranking parameters. This project aims to assist colleges and universities in assessing and improving their performance in various ranking criteria.


## Project Overview

The goal of this project is to build a predictive model that can accurately estimate NIRF rankings using machine learning techniques. The model identifies critical features influencing rankings, such as faculty qualifications, research output, and infrastructure, and provides actionable insights for improvement.

## Libraries Used

- **Python**
- **NumPy**
- **Pandas**
- **Scikit-Learn**
- **Matplotlib**

## Features

- **Exploratory Data Analysis (EDA):** Identified key features influencing rankings using statistical and graphical techniques.
- **Data Preprocessing:** Cleaned and transformed raw data using **NumPy**, **Pandas**, and **Seaborn**, ensuring data quality and consistency.
- **Model Evaluation:** Tested multiple regression algorithms, selecting **Random Forest Regressor** as the best-performing model.
- **Model Performance:** Achieved a high accuracy of **97%**, with performance metrics:
  - **Mean Absolute Error (MAE):** 2.3
  - **Mean Squared Error (MSE):** 5.4
  - **Root Mean Squared Error (RMSE):** 2.32
- **Visualization:** Visualized feature importance and model predictions using **Matplotlib** for enhanced interpretability.


## Methodology

1. **Data Collection:** Used NIRF Engineering College Rankings dataset with over 900 entries.
2. **Data Cleaning:** Handled missing values, normalized data, and performed feature engineering.
3. **Exploratory Data Analysis:** Identified patterns and relationships among features.
4. **Model Training:** Trained and tested multiple regression models.
5. **Model Selection:** Finalized the **Random Forest Regressor** based on evaluation metrics.
6. **Visualization:** Created plots to analyze and interpret the results effectively.



## Future Scope
1. **Expand the Dataset:** I plan to enhance the dataset by including additional features and increasing the number of entries to improve the model's accuracy and generalization capabilities.
2. **Explore Advanced Models:** I aim to experiment with advanced machine learning models, such as Gradient Boosting, XGBoost, and Neural Networks, to further optimize performance and achieve higher predictive accuracy.
3. **Develop a Web Application:** I intend to create a user-friendly web application that will allow users to input relevant data and obtain NIRF ranking predictions easily, making the tool accessible to a broader audience.

