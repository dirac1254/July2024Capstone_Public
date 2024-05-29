# July2024Capstone_Public

# Capstone Project: Used Vehicle Price Prediction

## Project Overview

### Problem Area

The automobile market is vast and dynamic, with numerous factors influencing the prices of vehicles. Understanding these factors and accurately predicting car prices is crucial for various stakeholders, including buyers, sellers, and dealerships. This project aims to develop a data-driven solution to predict car prices based on a range of features.

### Those Affected

- **Buyers**: Individuals looking to purchase a car can benefit from accurate price predictions to make informed decisions.
- **Sellers**: Car owners and dealerships can set competitive prices for their vehicles.
- **Dealerships**: Businesses can optimize their pricing strategies to maximize profits and turnover.

### Proposed Data Science Solution

To address the problem of car price prediction, we propose a machine learning model that leverages historical data on car attributes and sale prices. The model will be trained to learn the relationships between various features (e.g., make, model, year, condition, mileage) and the selling price. This predictive model can then be used to estimate the price of a car based on its characteristics.

### Impact of the Solution

- **Informed Decision Making**: Buyers and sellers can make more informed decisions with access to accurate price predictions.
- **Competitive Pricing**: Dealerships can set competitive prices, enhancing market efficiency.
- **Market Insights**: Insights derived from the model can help understand the factors that significantly influence car prices.

### Dataset Description

The dataset used for this project contains detailed information on cars and their sale prices. The data includes various attributes that are expected to influence the price, such as the car's make, model, year, condition, odometer reading, and more.

#### Data Dictionary

- **year**: Year the car was manufactured.
- **make**: Manufacturer of the car (e.g., Ford, Toyota).
- **model**: Model of the car (e.g., Mustang, Corolla).
- **trim**: Specific trim or version of the car model.
- **body**: Type of car body (e.g., sedan, SUV).
- **transmission**: Type of transmission (e.g., automatic, manual).
- **vin**: Vehicle Identification Number.
- **state**: State where the car is located.
- **condition**: Condition of the car (e.g., new, used).
- **odometer**: Mileage of the car.
- **color**: Exterior color of the car.
- **interior**: Interior color of the car.
- **seller**: Seller of the car.
- **mmr**: Manheim Market Report (MMR) value, an indicator of wholesale prices.
- **sellingprice**: Final selling price of the car.
- **saledate**: Date when the car was sold.

### Changes or Refinements

Based on the initial Area of Interest submission, some refinements have been made to the scope and methodology of the project. The following updates have been incorporated:
- **Feature Engineering**: Additional features, such as the car's age and whether it was sold in the same year it was manufactured, have been created to enhance the model's predictive power.
- **Data Cleaning**: Extensive data cleaning steps have been implemented to handle missing values and ensure data quality.
- **Modeling Approach**: A variety of machine learning models, including Random Forest and Gradient Boosting, will be explored to identify the best-performing model.

## Getting Started

### Prerequisites

To run the code in this repository, you will need the following libraries:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

You can install the required libraries using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn

