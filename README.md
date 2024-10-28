# House Price Prediction Using Regression and Random Forest Models

## Project Overview
This project aims to predict house prices using a variety of property features, such as square footage, number of bathrooms, bedrooms, and the year the house was built. Three different models—Linear Regression, Random Forest, and Decision Tree—were evaluated to determine which one best captures the factors influencing house prices.
## Files Included
- `house_price_prediction.py`: The main script for data cleaning, analysis, and model training.
- `data_assignment2.csv`: The dataset used in the analysis.
- `requirements.txt`: Python libraries required to run the project.

## Key Steps
1. **Data Cleaning & Wrangling**: Handled missing values, data types, and standardized features.
2. **Exploratory Data Analysis (EDA)**: Visualized key features and their relationships with house prices.
3. **Feature Selection**: Identified important features such as `sqft_living`, `bedrooms`, `bathrooms`, and `sqft_above`.
4. **Modeling**:
   - Linear Regression
   - Random Forest Regression
   - Decision Tree Regression

5. **Model Evaluation**: Assessed model performance using Mean Squared Error (MSE) and R-squared metrics to identify the most effective model.
6. **Model Comparison and Results**:
   After evaluating each model:
   - Linear Regression had the highest R-squared value (3.05%) and the lowest MSE, indicating it performed best on this dataset.
   - Random Forest performed slightly worse, with a lower R-squared and slightly higher MSE.
   - Decision Tree had the poorest performance, with a negative R-squared value, suggesting it overfits and fails to generalize well.
While Linear Regression showed the best results, the low R-squared across models suggests that additional features or advanced models might be needed for improved accuracy.

## Getting Started

### Dependencies
To install the required dependencies, run:
```bash
pip install -r requirements.txt
Project By Ibrahim Denis Fofanah, MSc Data SCience- Pace University




