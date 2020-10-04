# Kaggle Problem Statement: [IEEE-CIS Fraud Detection](https://www.kaggle.com/c/ieee-fraud-detection/overview/description)

## Background:
Imagine standing at the check-out counter at the grocery store with a long line behind you and the cashier not-so-quietly announces that your card has been declined. In this moment, you probably aren’t thinking about the data science that determined your fate.

Embarrassed, and certain you have the funds to cover everything needed for an epic nacho party for 50 of your closest friends, you try your card again. Same result. As you step aside and allow the cashier to tend to the next customer, you receive a text message from your bank. “Press 1 if you really tried to spend $500 on cheddar cheese.”

While perhaps cumbersome (and often embarrassing) in the moment, this fraud prevention system is actually saving consumers millions of dollars per year. Researchers from the [IEEE Computational Intelligence Society](https://cis.ieee.org/) (IEEE-CIS) want to improve this figure, while also improving the customer experience. With higher accuracy fraud detection, you can get on with your chips without the hassle.

## Description:
This project includes the following tasks performed in iPython:
* Exploratory data analysis
* Correlation analysis
* Data Visualization
* Building a model to predict whether a transaction is fraudulent

Python libraries used: Pandas, NumPy, SciPy, Scikit-learn, Matplotlib and Seaborn.

## Problem Statements:
1. Visual analysis of Fradulent V/s Non-Fraudulent transactions on filtering by:
   * Transaction Date
   * Transaction Amount
   * Product Code
   * Card - Issuer and Type
   * Billing Region
   * Billing Country
   * Distance Measurement
   * Email domain of purchaser V/s recepient
   * Device Type
   * Device Info
2. Find country code with highest frequency of transaction and analyze transaction frequency against time of day
3. Find the most expensive and most cheapest products
4. Find correlation between time of day and purchase amount
5. Find 2 interesting plots:
   * Analyzed transaction frequency of Fraudulent and Non-fraudulent transactions with Time of Day
   * Analyzed transaction amount of Fraudulent and Non-fraudulent transactions with Time of Day
6. Train models on training dataset and predict if a transaction is fraudulent for the test data set. Algorithms used:
   * Logistic Regression
   * Light GBM
   * AdaBoost
