# Machine Learning on Housing Market

## Project Overview
This project demonstrates the application of machine learning techniques to predict house prices using a real-world housing dataset. The analysis compares the performance of different regression models (Ordinary Least Squares and K-Nearest Neighbors) on housing market data, including comprehensive data exploration and statistical validation.

## Dataset
- **Source**: House_listings_dataset.csv
- **Features**: Number of bedrooms, bathrooms, lot size (acres), house size (sq ft), state, and property type
- **Target**: House price
- **Size**: Multiple processed dataframes with cleaned and NA-dropped versions

## Project Structure
```
Code/
├── project-data-exploration.ipynb   # Exploratory Data Analysis (EDA)
├── project-knn.ipynb                # K-Nearest Neighbors regression model
└── project-ols.ipynb                # Ordinary Least Squares regression model
Data/
├── House_listings_dataset.csv       # Original dataset
├── cleaned_df.csv                   # Preprocessed data
└── na_dropped_df.csv                # Data with NA values removed
```

## Key Features & Models
- **Data Exploration**: Statistical analysis, visualization of feature distributions, correlation analysis, and data quality assessment
- **OLS Regression**: Linear regression model with detailed statistical diagnostics, residual analysis, and model interpretation
- **KNN Regression**: Non-parametric k-nearest neighbors model with hyperparameter tuning and cross-validation

## Resume Highlights

- **Conducted comprehensive exploratory data analysis (EDA)** on housing market dataset with 1000+ listings, visualizing feature distributions, correlations, and identifying data quality issues to inform modeling decisions

- **Implemented and compared multiple regression models** (OLS and KNN) using Python/Scikit-learn, evaluating performance metrics (R², RMSE, MAE) and selecting optimal hyperparameters through cross-validation

- **Performed statistical modeling with OLS regression**, including residual diagnostics, feature scaling, handling of categorical variables through one-hot encoding, and interpretation of regression coefficients

- **Developed feature engineering pipeline** to standardize numeric features and encode categorical variables (state, property type), improving model generalization and prediction accuracy

- **Validated model assumptions and robustness** through residual analysis, correlation testing, and comparative model evaluation to ensure reliable housing price predictions

## Technologies Used
- **Languages**: Python 3
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib
- **Methods**: Linear Regression (OLS), K-Nearest Neighbors, Cross-validation, Feature Scaling, One-Hot Encoding

## How to Use
1. Navigate to the `Code/` directory
2. Open any of the Jupyter notebooks to view the analysis
3. Notebooks can be run sequentially starting with `project-data-exploration.ipynb` for context
4. Dataset files are located in the `Data/` directory

## Author
Azaan Patil
