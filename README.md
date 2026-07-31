German Cars Market Analysis using Exploratory Data Analysis (EDA)

Project Overview

This project analyzes 46,405 German used-car listings collected from AutoScout24, one of Europe's largest online automobile marketplaces. The objective is to understand how factors such as horsepower, mileage, fuel type, transmission, production year, and vehicle condition influence vehicle pricing and market behavior.
The project follows a complete data analytics workflow including data cleaning, exploratory data analysis, statistical analysis, visualization, and business recommendations.

Objectives

Clean and preprocess the raw dataset
Perform Exploratory Data Analysis (EDA)
Analyze pricing trends across multiple vehicle attributes
Discover relationships using statistical and correlation analysis
Generate business insights and recommendations for dealerships and marketplaces

Dataset Information
| Feature       | Details                        |
| ------------- | ------------------------------ |
| Dataset       | German Used Cars (AutoScout24) |
| Records       | **46,405**                     |
| Variables     | **9**                          |
| Years Covered | **2011–2021**                  |
| Source        | AutoScout24 (Kaggle)           |

Features

Brand
Model
Price (€)
Mileage
Horsepower
Fuel Type
Transmission
Production Year
Offer Type

Tech Stack

Python
Pandas
NumPy
Matplotlib
Jupyter Notebook

Project Workflow
Raw Dataset
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Statistical Analysis
      │
      ▼
Correlation Analysis
      │
      ▼
Data Visualization
      │
      ▼
Business Insights
      │
      ▼
Recommendations

Data Cleaning

The dataset was cleaned by:
Handling missing values
Removing incomplete records
Correcting data types
Validating inconsistent values
Eliminating duplicate records

Cleaning Result

Original Records: 46,405
Clean Records: 46,071
Exploratory Data Analysis

The analysis includes:

Descriptive Statistics
Distribution Analysis
Correlation Analysis
Price Analysis
Brand & Model Analysis
Fuel Trend Analysis
Transmission Trend Analysis
Production Year Analysis
Market Segmentation

Key Insights

1. Horsepower strongly influences price
Strong positive correlation (r = +0.75)
Horsepower is the strongest pricing indicator.

2. Automatic transmission is becoming dominant
Automatic cars surpassed manual cars in 2018
Premium vehicles are increasingly automatic.

3. The market is budget-oriented
76.6% of listings are priced below €20,000
Only 3.2% cost more than €50,000.

4. Electric & Hybrid vehicles are increasing
Electric and hybrid listings consistently increase in newer production years.
Electrified vehicles occupy larger shares in higher price categories.

5. Production year affects pricing
Newer vehicles generally command higher prices.
Older vehicles dominate the budget segment.

6. Volkswagen dominates the marketplace
Volkswagen contributes the highest number of listings.
Audi, BMW, and Mercedes-Benz lead in premium pricing.

Business Recommendations

Expand inventory of Electric and Hybrid vehicles.
Prioritize Automatic transmission vehicles in premium segments.
Use horsepower-based pricing for mainstream vehicles.
Adopt comparable-market pricing for luxury vehicles.
Monitor changing fuel preferences.
Plan inventory based on production year trends.

Repository Structure
German-Cars-Market-Analysis/
│
├── German-cars-Analysis.ipynb
├── German_Cars_Market_Analysis_EDA.pptx
├── dataset.csv
├── images/
├── README.md
└── requirements.txt

Future Scope

Build a Machine Learning price prediction model.
Develop an interactive dashboard using Power BI or Tableau.
Integrate external market and registration datasets.
Deploy the project as a web application for real-time vehicle price estimation.

Results

Cleaned 46,405 real-world listings.
Produced 20+ visualizations.
Identified pricing drivers and market trends.
Delivered actionable business recommendations for inventory planning and pricing decisions.
