# predictive-analytics-sales-forecasting
Analyze historical sales data and use machine learning to predict future sales trends.
# Predictive Analytics Using Historical Sales Data

## Project Overview

This project focuses on using historical sales data to analyze past trends, identify seasonal patterns, build a predictive model, and forecast future sales.

The project demonstrates how predictive analytics and machine learning can be used to support data-driven business decisions such as sales planning, demand estimation, and future performance analysis.

---

## Project Objective

The main objectives of this project are:

- Analyze historical sales data
- Clean and preprocess the dataset
- Identify sales trends and seasonal patterns
- Perform exploratory data analysis
- Create useful time-based features
- Build a regression-based predictive model
- Evaluate the performance of the model
- Compare actual sales with predicted sales
- Forecast future sales
- Visualize historical and forecasted trends

---

## Dataset

The dataset contains daily historical sales records from **2021 to 2025**.

### Dataset Details

- **Number of Records:** 1,826
- **Time Period:** January 2021 – December 2025
- **Frequency:** Daily
- **Target Variable:** Sales

### Dataset Columns

| Column | Description |
|---|---|
| Date | Date of the sales record |
| Sales | Total sales for the day |
| Orders | Number of orders for the day |
| Average_Order_Value | Average value of each order |

---

## Technologies Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Scikit-learn**
- **Google Colab**
- **Jupyter Notebook**

---

## Machine Learning Model

### Linear Regression

Linear Regression was used to build the predictive model.

The model learns the relationship between historical time-based features and sales and uses these patterns to predict future sales.

### Features Used

The following features were created from the date information:

- Time Index
- Month
- Month Sine
- Month Cosine
- Day of Week
- Day of Week Sine
- Day of Week Cosine

These features help the model understand both long-term trends and recurring seasonal patterns.

---

## Project Workflow

```text
Historical Sales Dataset
          ↓
Data Loading
          ↓
Data Cleaning
          ↓
Data Exploration
          ↓
Trend Analysis
          ↓
Feature Engineering
          ↓
Train-Test Split
          ↓
Linear Regression
          ↓
Sales Prediction
          ↓
Model Evaluation
          ↓
Actual vs Predicted Analysis
          ↓
Future Sales Forecast
          ↓
Visualization
