# House Price Prediction using Machine Learning
This repository contains a Machine Learning project designed to predict the market price of houses based on various physical and location-based features. The project utilizes a Linear Regression model to provide accurate real estate valuations.

 # Project Overwiew:
 Valuing real estate manually is complex and often subject to humans bias. This project demonstrates how a supervised statistical learning approach can capture spatial and structural variables to generate automated,objective property appraisals.

# Key Features Summary:
 1)Synthesized Real  Estate Engine:
 Embedded programmatic data generation modeling real-world economic features.
 
 2)Feature Core Analysis:
 In-depth Exploration Data Analysis(EDA)evaluating multi-collinearity and parameter relationships.

 3)High predictive capacity:
 Trained structural models showing exceptional convergence to target metrics (R^2=0.93).

# Dataset Architecture
The core system programmatically builds and acts upon a custom structured dataset (HPP(Data set.ML).csv) tracking 15 historical standard real estatae profiles:

# Feature Name            Data Type               Description
Square_feet               Integer                 Total Interior liveable
                                                  area in square feet.
                                                  
Bedrooms                  Integer                 Total count of bedrooms
                                                  in the housing unit.
 
Bathrooms                 Integer                 Total count of bathrooms 
                                                  available.

House_age                 Integer                 Age of the property since
                                                  original construction(Years)

Location_score            Integer                 Normalized spatial/neighborhood
                                                  quality score (scale: 1-10).

Price(USD)                Integer                 target Variable:Final market 
                                                  transcation value of the home.
                                                  
# Requirements & Installation
Make sure you have Python installed(preferably via the Anaconda distrubtion environment).

# Prerequisites
Install the required scientific computing and visualization libraries:
[pip install pandas numpy matplotlib seaborn scikit-learn]

# Installation
1). Clone the repository:
[https://github.com/YOUR_USERNAME/House-Price-Prediction-ML.git]

2). Open and execute the notebook:
[jupyter notebook House_Price_Prediction_ML.ipynb]

# Machine Learning Workflow
1) Data Engineering: Automatically defines and checks for null values or missing components using pandas descriptive operations.

2) Exploratory Visualizations: Draws correlation maps and spatial distribution plots using matplotlib and seaborn to understand structural factors.

3) Data Splitting: Segregates target features from spatial/structural predictors (X and y) and segments data utilizing a 20% validation holdout strategy (train_test_split).

4) Model Execution: Employs Ordinary Least Squares (OLS) via sklearn.linear_model.LinearRegression to fit coefficients and minimize loss boundaries.

# Performances & Metrics
The model evaluation produced stable mathematical metrics across testing distributions:
* Model Fit (R^2 Score): 93% — Proving the explanatory parameters cover the vast majority of real-world value variance.

* Mean Absolute Error (MAE): ~$24,233 — Represents a tight, localized boundary perfectly acceptable within modern
  residential evaluation protocols.

Key Data Insights:

* Primary Drivers: Statistical feature importances identify Square Footage and Location Score as having the largest statistical weight on valuation shifts.

* Trend Analysis: Visual metrics confirm strong linear behaviors; as net area scales, price curves shift up consistently.

* Generalization Check: An isolated reference test on an unseen 2,500 sq.ft. asset correctly estimated a target market price of approximately $431,000.

# Repository Tree Structure
├── House_Price_Prediction_ML.ipynb   # Main Jupyter Notebook holding data, source code & metrics
├── HPP(Data set.ML).csv               # Programmatically exported housing transaction dataset
└── README.md                         # Project documentation and summary
