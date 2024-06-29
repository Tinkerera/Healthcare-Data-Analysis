# Healthcare Data Analysis

This project involves analyzing healthcare data to explore various factors influencing employee attrition. It includes data visualization, preprocessing, and modeling to predict attrition rates.

## Project Overview

1. **Data Loading and Exploration**: 
   - The dataset is loaded and basic statistics are obtained, including shape, columns, and data types.

2. **Data Visualization**:
   - Visualizations are created to understand distributions and relationships in the data, including:
     - Data types of columns
     - Attrition rates
     - Distribution of age
     - Monthly income by department and overtime status
     - Total working years by age
     - Job satisfaction levels

3. **Data Manipulation**:
   - Unnecessary columns are removed.
   - Missing values are checked, and basic statistics are summarized.
   - Numerical data is standardized using z-scores.

4. **Data Preprocessing**:
   - Categorical data is encoded using label encoding and ordinal encoding.
   - Correlation matrix analysis to check for multicollinearity among variables.

5. **Model Selection and Evaluation**:
   - Various classification models are trained to predict attrition, including:
     - Logistic Regression
     - Decision Trees
     - Random Forest
     - Gradient Boosting
     - XGBoost
     - LightGBM
     - Support Vector Machines
     - Naive Bayes
     - Neural Networks
   - Each model is evaluated based on accuracy scores.
   - The best-performing model is identified.

6. **Logistic Regression and Hyperparameter Tuning**:
   - Logistic Regression is further explored with hyperparameter tuning using GridSearchCV.
   - The best parameters are identified, and model performance is evaluated using accuracy, confusion matrix, classification report, and ROC curve.

7. **Model Saving**:
   - The best model is saved for future use.

## Dependencies

- Python
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- lightgbm
- catboost
- joblib

## Usage

1. Load the dataset and explore it using the provided visualizations.
2. Preprocess and manipulate the data as necessary.
3. Train various models and evaluate their performance.
4. Use the best model for predictions on new data.

## Conclusion

This project provides insights into factors affecting employee attrition and demonstrates how machine learning models can predict attrition rates effectively.

