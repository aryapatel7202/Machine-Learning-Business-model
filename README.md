# Simple Linear Regression: Administration vs. Profit

This project predicts company profit using only administration spending via a simple (univariate) linear regression model.

## Requirements

- pandas
- numpy
- matplotlib
- scikit-learn

## How to Run

1. Place `1000_Companies.csv` in the working directory.
2. Ensure all dependencies are installed (`pip install pandas numpy matplotlib scikit-learn`).
3. Run the Python script.

## What the Code Does

- Loads data and selects relevant columns
- Splits data into training & test sets
- Trains a linear regression model
- Plots actual vs. predicted profits
- Prints performance metrics and regression equation

## Files

- `1000_Companies.csv`: Input dataset
- `main.py`: Script (the code provided)

## Output

- Scatter plot (`matplotlib`)
- Metrics: R2, MAE, MSE
- Printed regression equation

## Project Description

This project demonstrates supervised regression on a real-world business dataset to predict **profit** based on **administration expenditures**. It utilizes Python data science libraries for practical business analytics and model evaluation, designed for learners and analysts exploring machine learning basics.
