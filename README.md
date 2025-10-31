Egypt Real Estate Data Analysis & Price Prediction

A project to clean, analyze, visualize, and predict real estate prices in Egypt using Python, Power BI, and machine learning techniques.
The project aims to uncover insights about the Egyptian housing market and build a predictive model to estimate property prices based on property features.

1. Introduction

This project focuses on analyzing a Real Estate Listings dataset collected from various regions in Egypt.
The dataset includes property details such as price, location, size, number of rooms, bathrooms, property type, and payment method.

The main objectives are:

To clean and preprocess raw property listings.

To extract insights and visualize price patterns across different locations.

To build a predictive model that estimates property prices.

To design an interactive Power BI dashboard summarizing market insights.

The project is divided into four main stages:

Data Preprocessing and Cleaning

Exploratory Data Analysis (EDA)

Feature Engineering and Modeling

Visualization and Dashboard Creation

2. Dataset Description

The dataset contains 19,924 rows (records) and 11 columns (features).
It represents real estate listings from various Egyptian cities and neighborhoods, covering multiple property types and payment options.

Key Features:

url – Link to the original listing.

price – The listing price of the property.

description – Short text describing the property.

location – City or district name.

type – Type of property (e.g., Apartment, Villa, Studio).

size – Property area (often in square meters).

bedrooms – Number of bedrooms.

bathrooms – Number of bathrooms.

available_from – Availability date or posting date.

payment_method – Indicates cash or installment options.

Detected Issues Before Cleaning:

Missing values in several columns (price, size, location).

Non-numeric symbols in numeric columns (e.g., “1,200,000 EGP”, “150 sqm”).

Duplicated or incomplete records.

Inconsistent text capitalization and spacing.

Outliers in price and size values.

🧹 These issues will be handled during preprocessing to ensure data quality and improve model performance.

3. Methodology
Data Cleaning and Preprocessing

Load and inspect the dataset using pandas and NumPy.

Handle missing values (imputation or removal).

Convert price and size to numeric formats.

Remove duplicates and invalid rows.

Detect and treat outliers using statistical methods (IQR/Z-score).
Deliverables: Clean dataset ready for analysis.

Exploratory Data Analysis (EDA)

Visualize price distributions and correlations.

Explore relationships between price, size, and location.

Identify most expensive and affordable regions.
Tools: matplotlib, seaborn
Deliverables: Visual insights and descriptive statistics.

Feature Engineering & Modeling

Encode categorical columns (e.g., type, location, payment_method).

Scale numerical features.

Train regression models (Linear Regression, Random Forest, XGBoost).

Evaluate model performance using MAE, MSE, and R².
Deliverables: Trained model for price prediction.

Visualization & Dashboard

Create an interactive Power BI Dashboard.

Display key KPIs: average price, top locations, price distribution, etc.

Integrate model predictions for better business insight.
Deliverables: Power BI dashboard + summary report.

4. Tools and Technologies

Python – Data cleaning, analysis, and modeling (pandas, NumPy, matplotlib, seaborn, scikit-learn).

Power BI – Dashboard creation and visualization.

Jupyter Notebook / VS Code – For scripting and reporting.

5. Expected Outcomes

A clean and structured dataset ready for analysis.

Visual insights into market trends and property values.

A machine learning model that predicts property prices.

An interactive Power BI dashboard summarizing findings.

A professional, well-documented project for portfolio presentation.

