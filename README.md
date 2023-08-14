# Predictive Machine Learning for Telco Customer Churn
![Project Logo](banner.jpg)

## Background
Currently, telecommunications service customers have numerous options and can easily switch subscriptions from one service provider to another. Marketing practitioners in this industry strive to prevent customers from switching to competing companies. Why is that? Because acquiring new customers is far more expensive than retaining loyal existing customers. Therefore, retaining existing customers is a high priority compared to acquiring new customers.

A common approach is to provide special pricing packages or bonuses to customers to prevent them from being tempted to switch to a competing company. However, if such offers are extended to all existing customers, the cost can become expensive as only a small fraction of customers tend to churn (unsubscribe) in general. A more effective approach is to ensure that special offers or bonuses are only given to specific customers known to have a propensity to churn.

## Table of Contents
- [Case Analysis and Goals](#case-analysis-and-goals)
- [Data Understanding](#data-understanding)
- [Explanatory Data Analysis](#explanatory-data-analysis)
- [Feature Engineering](#feature-engineering)

## Case Analysis and Goals
In this case, a predictive model will be developed for a telecommunications company with promotional programs that will only be offered to a group of customers deemed susceptible to churn. To make this more effective, Machine Learning is required to identify this customer group. The goal of this predictive model is to generate a churn score for each customer, indicating whether they are predicted to unsubscribe or not. This predictive model will use predictors based on patterns of customer internet service usage on the company's network.

How can the created prediction discern customer usage patterns? An individual's past behavior can serve as a reference point for understanding their future behavior. These behaviors are what will be analyzed from the available data. By identifying the signs that indicate someone is likely to churn, the company can take measures to prevent them from actually unsubscribing.

## Data Understanding
At this stage, Data Understanding is performed with the aim of gaining a deeper understanding of the data characteristics being analyzed before before getting into Explanatory Data Analysis. Some steps of preparation are conducted as a slight cleanse process, those are data formatting and duplicates. Futher preparation processes will go along with in Explanatory Data Analysis. Please find the detailed process in [Data Understanding](Data_Understanding.ipynb).

## Explanatory Data Analysis
Explanatory Data Analysis is very critical before building a predictive model. This includes identifying patterns, trends, relationships, anomalies in data, as well as revealing insights that may not be visible directly. As for visualization, we will use library from **Matplotlib** and **Seaborn**. Please find the detailed process in [Explanatory Data Analysis](Explanatory_Data_Analysis.ipynb).

## Feature Engineering
Before doing machine learning modeling, a process is needed to prepare the raw data into ready-to-use data. In other words, this process is referred to as feature engineering. By doing good feature engineering, machine learning models can provide more accurate and better results in predicting target variables. Please find the detailed process in [Feature Engineering](Feature_Engineering.ipynb)
