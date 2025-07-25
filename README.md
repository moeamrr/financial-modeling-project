# Financial Modeling Project – MSc in FinTech & Policy

This project was developed as part of my postgraduate studies at the University of Surrey, combining theoretical finance with practical, real-world data analysis using Python. It focuses on analyzing company performance through automated financial data retrieval, regression modeling, and visualization, with an emphasis on Cost of Equity, Beta analysis, and risk assessment.

## Project Overview
The goal of this notebook is to guide stakeholders through:
- The collection and analysis of financial data
- Understanding a company's risk (beta) and market sensitivity
- Performing linear regression between a stock and the S&P 500
- Plotting performance trends and calculating alpha & beta for investment insights

Users are prompted to enter any 3 company ticker symbols, allowing custom analysis for firms of interest.

## Key Concepts Covered
- Cost of Equity
- Beta (Systematic Risk)
- Alpha (Excess Return)
- Linear Regression using Sklearn
- CAPM theory (implied)
- Time Series Financial Data (from Yahoo Finance)

## Tools & Libraries Used
- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- yfinance for stock data retrieval
- Scikit-learn (for linear regression)

## Sample Features
- User inputs 3 stock ticker symbols
- Downloads and analyzes 10 years of price data (2014–2024)
- Compares company returns to S&P 500 index returns
- Plots a line of best fit showing correlation between stock and market
- Prints alpha and beta to measure return and risk

## Why This Project Matters
This project demonstrates:
- Practical application of financial theories using code
- Real-world data modeling and investment analysis
- Ability to bridge finance and tech — critical for roles in FinTech, Risk, or Product Analytics

## Example Output
Alpha (intercept) for MSFT: 0.00027  
Beta (slope) for MSFT: 1.02  
*A beta above 1 implies the stock is more volatile than the market.*

## File Structure
financial-modeling-project/  
├── FINAL.ipynb      # Main Jupyter notebook with all analysis  
└── README.md        # This file
