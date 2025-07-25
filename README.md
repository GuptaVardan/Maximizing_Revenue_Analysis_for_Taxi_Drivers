# Maximizing Revenue for Taxi Cab Drivers Through Payment Type Analysis

## Problem Statement
In today's competitive world of taxi services, maximizing revenue is crucial for both long-term success and driver satisfaction. This project investigates how different payment methods (credit card vs. cash) affect fare pricing and overall driver revenue.

## Objective
Analyze the impact of payment methods on taxi fares using statistical techniques and Python. The goal is to discover whether there is a significant difference in fares based on payment method, helping drivers optimize their earnings.

## Dataset
- The dataset contains taxi trip records with features such as passenger count, payment type, fare amount, trip distance, and trip duration.
- Data cleaning steps include handling missing values, correcting data types, removing duplicates, and filtering outliers.

![Dataset Description](data/image.png)


## Approach
1. **Data Loading & Cleaning**: Import the dataset, clean data, and prepare features for analysis.
2. **Feature Engineering**: Extract relevant features and calculate trip duration.
3. **Exploratory Data Analysis (EDA)**: Visualize and summarize key variables.
4. **Statistical Analysis**: Compare fares by payment type and test for significant differences.
5. **Modeling**: Use regression analysis to understand relationships between trip features and fare amount.

## How to Run
1. Install dependencies:
   ```bash
   python -m venv venv
   venv\Scripts\activate
   pip install -r requirements.txt
   ```
2. Open `Maximizing_Revenue.ipynb` in Jupyter Notebook or VS Code.
3. Run cells sequentially to reproduce the analysis and results.

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas, numpy, matplotlib, seaborn, scikit-learn, plotly

## Results
- Insights into how payment type affects fare amount.
- Recommendations for drivers to maximize revenue based on payment preferences.

## License
This project is for educational and research purposes.
