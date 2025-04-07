# 🏡 Bengaluru House Prices Analysis

## Overview

This project analyzes house prices in Bengaluru using various data science techniques. The dataset contains information about different properties, including area type, availability, location, size, society, total square feet, number of bathrooms, balconies, and price.

## Tools and Libraries Used

- 🐼 **Pandas**: For data manipulation and analysis.
- 📊 **NumPy**: For numerical computations.
- 🤖 **Scikit-learn**: For implementing machine learning models.

## Methodology

1. **Data Preprocessing**:
    - Loaded the dataset using Pandas.
    - Cleaned the data by handling missing values and converting data types.
    - Created new features from existing ones to enhance the model's performance.

2. **Exploratory Data Analysis (EDA)**:
    - Visualized the distribution of house prices.
    - Analyzed the relationship between different features and house prices.
    - Identified key factors affecting house prices.

3. **Model Building**:
    - Split the data into training and testing sets.
    - Applied various regression models to predict house prices, including:
        - 📈 Linear Regression
        - 🌳 Decision Tree Regression
        - 🌲 Random Forest Regression
    - Evaluated the performance of each model using metrics like Mean Absolute Error (MAE) and R-squared.

4. **Model Selection**:
    - Compared the performance of different models.
    - Selected the best model based on evaluation metrics.

## Functions

- **Data Loading**: Function to load and preprocess the data.
- **EDA**: Functions to visualize and analyze the data.
- **Model Training**: Functions to train different regression models.
- **Model Evaluation**: Functions to evaluate the performance of models.
- **Model Selection**: Function to select the best model based on evaluation metrics.

## Results

- The best model for predicting house prices was found to be [insert best model here], which achieved the lowest MAE and highest R-squared value.
- Key factors affecting house prices include location, size, and total square feet.

## Conclusion

This project demonstrates the application of data science techniques to analyze and predict house prices in Bengaluru. The selected model can be used to make informed decisions about property investments.

## How to Use

1. Clone the repository:
    ```bash
    git clone [repository URL]
    ```
2. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```
3. Run the analysis:
    ```bash
    python analysis.py
    ```
