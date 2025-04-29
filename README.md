# Book Purchases Pattern Prediction

## Overview

This repository contains the analysis for the Charles Book Club project. The primary goals were to:
1.  Predict which customers were likely to purchase a specialty travel book ("The Art History of Florence").
2.  Identify common book co-purchase patterns among different book genres using Market Basket Analysis.

The analysis uses historical customer transaction data to build a predictive model and derive actionable insights for targeted marketing and cross-selling strategies.

## Key Analysis Steps

*   **Data Exploration & Cleaning:** Initial analysis and preparation of the customer data.
*   **Predictive Modeling:** Development of a Random Forest Classifier (using SMOTE to handle class imbalance) to predict purchases of the "Florence" book. Feature importance analysis was also conducted.
*   **Market Basket Analysis:** Application of the Apriori algorithm to find frequent itemsets and generate association rules between book genres.

## Files in this Repository

*   `purchase_prediction_notebook.ipynb`: The main Jupyter Notebook containing all Python code for data loading, cleaning, exploratory data analysis (EDA), modeling, and market basket analysis.
*   `purchase_prediction_notebook.pdf`: A PDF version of the notebook for easy viewing.
*   `book_purchase_pattern_prediction_report.pdf`: A detailed report summarizing the project's methodology, findings, insights, and recommendations. *(Please update the file extension)*
*   `BookClub.xlsx`: The raw customer transaction data used for the analysis. *(Please update the file extension if necessary - the notebook likely uses the CSV version)*


## Key Findings Summary

*   Strongest predictors for the specialty book purchase: Customer monetary value, tenure (time since first purchase), and recency of purchase.
*   The classification model achieved reasonable accuracy but struggled with recall for the minority (buyer) class.
*   Market Basket Analysis revealed strong co-purchase patterns, particularly between Youth/DIY books and Cookbooks/Children's books.

## Tech Stack
*  Python
*  Pandas (Data Manipulation)
*  NumPy (Numerical Operations)
*  Matplotlib & Seaborn (Data Visualization)
*  Scikit-learn (Machine Learning - Model Selection
*  Random Forest, Metrics)
*  imblearn (SMOTE for Imbalance)
*  MLxtend (Apriori Algorithm)

## Portfolio
*  For a more detailed project description and portfolio, ckeck out: https://lapis-school-f5e.notion.site/Predicting-Book-Purchases-Uncovering-Purchase-Patterns-1e4ca101e4698026bdbcf3d9a0a60830?pvs=4

