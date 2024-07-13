# EDA
 
Exploratory Data Analysis (EDA) is an approach in data analysis that uses various techniques to maximize insight into a dataset, uncover underlying structure, analyze relationships between variables, detect outliers and anomalies, test underlying assumptions, and feature selection for training Machine Learning models.


EDA helps you know about the best candidates for features based on their relationship with the target variable and each other, their relevance, and their predictive power.


Below is the process you can follow while performing EDA for Feature Selection:

1. Begin by getting familiar with the dataset. It includes understanding the size, scope, and nature of the data (structured vs. unstructured), identifying each feature and its type (numerical, categorical), and recognizing the target variable.
2. Identify and handle missing values by imputation, deletion, or estimation, depending on their nature and the proportion of missing data.
3. Analyze the distribution of each feature using histograms, density plots, or bar charts for categorical variables.
4. Conduct correlation analysis using Pearson, Spearman, or Kendall correlation coefficients to assess the relationship between numeric features and the target variable.
5. Utilize scatter plots, pair plots, and heat maps to explore relationships between features.
6. Based on insights gained through EDA, manually remove redundant features, features with very little variance, or features highly correlated with others.


The given dataset (dynamic_pricing) consists of data related to ride-sharing service costs, encompassing various factors that could influence the dynamic pricing model of rides.

Our goal is to identify the most important features for predicting the Historical_Cost_of_Ride.
