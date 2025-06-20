# Greenhouse Gas Emission Prediction Project
Supply Chain Emission Modeling Using Industry and Commodity Data (2010-2016)

<br>

## Problem statement
We have annual supply chain emission data from 2010-2016 categorized into industries and commodities. The goal is to develop a regression model that can predict the Supply Chain Emission Factors with Margins on descriptive and quality metrics (substance, unit, reliability, temporal/ geographical/ technological/ data collection correlations, etc.) 

## Project Goal
To analyze and predict greenhouse gas(GHG) emission from various U.S. industries and commodities using the official dataset from [data.gov](https://catalog.data.gov/dataset/supply-chain-greenhouse-gas-emission-factors-for-us-industries-and-commodities).

![68747470733a2f2f6564672e6570612e676f762f4550414c6f676f2e737667](https://github.com/user-attachments/assets/c43b97ec-e3ce-40c2-8732-daee0c351cd9)

### Source
[Supply Chain Greenhouse Gas Emission Factors](https://catalog.data.gov/dataset/supply-chain-greenhouse-gas-emission-factors-for-us-industries-and-commodities)

### Tools
Python, Pandas, Scikit-learn, Matplotlib, Seaborn

## 📂 Dataset Overview
This dataset contains supply chain emission factors associated with various U.S. industries and commodities.
**Key Columns**
- `Code`: Industry classification code
- `Industry_Name`: Name of the industry
- `Commodity`: Item or commodity name
- `GHG_Emissions_kgCO2e`: GHG emissions per unit (kg CO2 equivalent)
- `Units`: Measurement units (e.g., [kg/2018 USD, purchaser price])

## 🧹 Data Preprocessing
Steps:
  - Handle missing values
  - Convert units where needed
  - Encode categorical features
  - Normalize/scale numeric columns

## 🤖 Model Building & Evaluation
We aim to predict GHG_Emissions_kgCO2e using regression models.

### Models to try:
  - Linear Regression
  - Random Forest

### Evaluation Metrics:
  - RMSE (Root Mean Squared Error)
  - MAE (Mean Absolute Error)
  - R² Score

### Steps:
- Step 1: Import Required Libraries
- Step 2: Load Dataset
- Step 3: Data Preprocessing (EDA+Cleaning+Encoding)
- Step 4: Training
- Step 5: Prediction and Evaluation
- Step 6: Hyperparameter Tuning
- Step 7: Comapartive Study and Slecting the Best model
