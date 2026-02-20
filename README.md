**Predicting Product Popularity on Amazon India (Beauty Category)**

This project focuses on designing and documenting a primary dataset to build a machine learning model that predicts whether a beauty product listed on Amazon India is likely to become popular.

**Problem Statement**

In the rapidly growing Indian beauty e-commerce market, sellers often struggle to decide the right price and discount strategy. Poor pricing decisions can lead to low sales and excess inventory.

The objective of this project is to use data-driven modelling to predict whether a product will achieve high customer engagement (measured by number of ratings).

**Dataset Overview**

Source: Amazon India (public search results page)

Collection Method: Manual primary data extraction

Dataset Size: 155 products × 6 features

Category: Beauty, Makeup, Skincare

Features Collected:

Product Name

Price (INR)

Original Price (INR)

Discount Percentage

Rating (out of 5)

Number of Ratings

**Labeling Strategy**

Products were classified as:

Popular (1): ≥ 5,000 ratings

Not Popular (0): < 5,000 ratings

This creates a binary classification problem.

** Data Cleaning & Feature Engineering**

Removed duplicate products

Handled missing values

Converted rating counts to numeric format

Created new features:

Price_to_Original_Ratio

Savings_INR

** Models Implemented**

Logistic Regression

Decision Tree

Random Forest

Gradient Boosting

K-Nearest Neighbours

Support Vector Machine (SVM)

** Best Model: Random Forest**

Test Accuracy: 84.6%

ROC-AUC: 0.894

**Key Insights**

Discount structure and rating score significantly influence product popularity.

Feature engineering improves prediction performance.

Tree-based ensemble methods performed better than linear models for this dataset.

**Applications**

Helps sellers optimize pricing before large-scale listing

Assists new brands in setting competitive launch prices

Supports learning in e-commerce analytics and ML classification
