# Fusion-Tech-Profit-Decline-Analysis

This project analyzes customer purchasing behavior and marketing effectiveness for FusionTech, an electronics retailer. Using a synthetic transaction dataset, the study focuses on churn prediction, customer value drivers, and marketing ROI optimization. Statistical and machine-learning models are applied to identify customers at risk of churn and evaluate the financial impact of retention and marketing strategies.

# Objectives

Engineer customer-level behavioral features from transaction data

Predict customer churn using Logistic Regression, Random Forest, and XGBoost

Identify key drivers of customer attrition

Quantify churn’s impact on gross margin

Compare marketing channels based on ROI and sales contribution

# Data

Source: Synthetic transaction dataset

Level: Transaction-level data aggregated to customer-level features

Key Fields:

Revenue, gross margin, discounts, returns

Transaction dates

Marketing campaign and channel exposure

Churn Definition:
Customers with no purchases in the last 180 days (relative to the dataset’s maximum date) are labeled as churned.

# Methods

Feature engineering: recency, frequency, AOV, total revenue, gross margin, return rate, marketing touches

Models:

Logistic Regression (baseline)

Random Forest

XGBoost (best-performing model by AUC)

Marketing analysis: ROI and profitability by channel

# Key Findings

Recency, frequency, and gross margin are the strongest churn predictors

Machine-learning models outperform logistic regression

Significant differences exist in marketing channel ROI, enabling spend optimization

# Tools & Technologies

R (tidyverse, modeling libraries)

Statistical modeling & machine learning

Marketing ROI analysis

# Business Impact

The results support strategic decision-making around:

Customer retention prioritization

Marketing budget reallocation

Maximizing customer lifetime value (CLV)
