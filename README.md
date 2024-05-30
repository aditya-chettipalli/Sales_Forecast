# E-commerce Sales Forecasting

## Abstract
In the dynamic landscape of e-commerce, understanding sales trends and predicting future patterns is paramount for strategic decision-making and sustained growth. This project focuses on a comprehensive analysis of e-commerce sales using state-of-the-art Machine Learning (ML) models for forecasting. We employ advanced ML techniques, including Linear Regression, Random Forest Regressor, and Gradient Boosting Regressor, alongside sophisticated time-series models such as ARIMA and SARIMA. The goal is to capture nuanced temporal patterns and enhance the accuracy of sales predictions. The predictive power of these models is evaluated through metrics such as Mean Absolute Error (MAE) and R-squared (R²).

## Objective
The core objective is to delve into the intricate factors influencing e-commerce sales, providing valuable insights for businesses to make proactive and informed decisions. By analyzing historical sales data and implementing innovative forecasting models, the project aims to offer a comprehensive roadmap for stakeholders navigating the e-commerce landscape.

## Dataset
The dataset, obtained from Kaggle, encompasses the transactional activities of a UK-based online retail company over a period from 01/12/2010 to 09/12/2011. Key attributes include transaction date, invoice number, product description, quantity sold, unit price, customer ID, and country.

## Methods
### Data Cleaning and Preprocessing
Missing Value Imputation: Addressed missing values using mean/median imputation.

Handling Duplicates: Identified and removed duplicate entries.

Feature Engineering: Derived new features such as day, month, and hour from timestamp data.

Data Splitting: Split data into 80% training and 20% testing sets.
### Model Selection
Linear Regression: Chosen for its simplicity and interpretability.

Random Forest: Selected for its ability to handle a large number of features and capture non-linear relationships.

Gradient Boosting: Employed for its effectiveness in capturing intricate patterns and dependencies.
### Forecasting Models
ARIMA: Utilized for uncovering short-term fluctuations and long-term trends.

SARIMA: Extended ARIMA by incorporating seasonal components.
### Evaluation Metrics
Mean Absolute Error (MAE): Measures the average absolute difference between predicted and actual values.

R-squared (R²): Indicates the proportion of the variance in the dependent variable that is predictable from the independent variables.

## Results
Model Performance

Linear Regression: MAE - 17.45, R² - 0.85

Random Forest: MAE - 2.12, R² - 0.53

Gradient Boosting: MAE - 6.90, R² - 0.55

## Discussion
The evaluation metrics indicate that Linear Regression achieved the highest R-squared value, signifying a strong correlation between predicted and actual sales. However, Random Forest exhibited the lowest MAE, implying minimal average prediction error. The choice between these models depends on the specific objectives, with Random Forest preferred for precision and Linear Regression for interpretability.
