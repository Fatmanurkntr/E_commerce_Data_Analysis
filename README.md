# Sales Data Analysis and Customer Segmentation

This project focuses on exploring, processing, and analyzing sales and customer data to gain insights into purchasing behaviors and predict customer review ratings. The objective is to understand customer segments, the relationship between various features, and ultimately build models that can predict customer review ratings, helping businesses make informed decisions about customer engagement and marketing strategies.

## Table of Contents

1. [Project Overview](#project-overview)
2. [Data Overview](#data-overview)
3. [Data Processing and Cleaning](#data-processing-and-cleaning)
4. [Feature Engineering](#feature-engineering)
5. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
6. [Data Preprocessing](#data-preprocessing)
7. [Model Building](#model-building)
8. [Model Evaluation](#model-evaluation)
9. [Visualizations](#visualizations)
10. [Conclusion](#conclusion)


## Project Overview

This project is designed to explore a sales dataset containing various customer attributes, transaction data, and reviews. The goal is to analyze customer behavior, identify purchasing patterns, and predict customer ratings. By performing feature engineering, cleaning the data, and building machine learning models, we can gain valuable insights into customer habits and segment customers based on their characteristics.

### Project Goals:

- **Customer Segmentation**: Understand customer segments based on age, purchase behavior, and review ratings.
- **Sales Trends**: Analyze time-based trends to predict seasonal sales patterns.
- **Predictive Modeling**: Build models to predict review ratings and identify repeat buyers.

## Data Overview

The dataset contains customer transaction records, including the following key features:

- **Customer ID**: Unique identifier for each customer.
- **Age**: Age of the customer.
- **Purchase Amount (USD)**: The amount spent by the customer in the transaction.
- **Previous Purchases**: The number of purchases made by the customer prior to this transaction.
- **Review Rating**: Customer's rating of the product (1-5 scale).
- **Time stamp**: Timestamp of the transaction.

The dataset is used to derive insights about customer behaviors, segment customers, and predict the likelihood of customers leaving high or low ratings.

## Data Processing and Cleaning

In the initial stage, we focus on cleaning the dataset to ensure that the data is usable for analysis. This includes:

1. **Handling Missing Values**: We identify missing values in the dataset and fill or remove them as appropriate.
   
2. **Date Parsing**: The 'Time stamp' column is converted to a proper datetime format for easier extraction of time-based features.
   
3. **Data Type Conversion**: Ensure correct data types for columns (e.g., converting categorical variables to object types and numerical variables to float/integer types).

4. **Removing Outliers**: Identifying and removing outliers in continuous variables to ensure data consistency.

## Exploratory Data Analysis (EDA)

EDA is an essential step to understand the dataset's structure, identify patterns, and uncover insights. The key steps in EDA for this project include:

- **Univariate Analysis**: Examine the distribution of individual features like Age, Purchase Amount, and Review Rating.
  
- **Bivariate Analysis**: Investigate relationships between features. For example, we look at the correlation between Age, Purchase Amount, and Review Rating.
  
- **Category Analysis**: We analyze the distribution of categorical features such as `Age Group` and `Repeat Buyer`.

## Visualizations

In addition to the analysis and modeling, visualizations play a crucial role in conveying insights:

- **Customer Segmentation**: We visualize customer segmentation based on age, purchase frequency, and repeat buyers.
- **Sales Trends**: We plot time series graphs to understand monthly and seasonal sales patterns.
- **Feature Distributions**: Histograms and box plots help visualize the distribution of numerical features.


## Feature Engineering

Feature engineering plays a vital role in improving model performance by creating new, meaningful variables from existing data. In this project, we create several new features to capture customer behaviors better:

### 1. **Age Grouping**:
Customers' ages are categorized into different age groups to segment customers by life stage.

### 2. **Purchase Frequency**:
This feature is derived from the number of previous purchases and the total purchase amount. It helps to identify repeat buyers and their purchasing habits.

### 3. **Repeat Buyers**:
This binary feature indicates whether a customer is a repeat buyer (made more than one purchase).

### 4. **Review Rating Group**:
We categorize the review ratings into 'Low', 'Medium', and 'High' to make the prediction task easier for modeling.
## Data Preprocessing

Data preprocessing includes preparing the data for machine learning models by scaling and encoding features.

### 1. **Standardization**:
Numerical features are standardized to ensure they are on the same scale and to improve model convergence.

### 2. **One-Hot Encoding**:
Categorical features are converted into binary columns using one-hot encoding.

### 3. **Label Encoding**:
For some categorical variables, we apply label encoding to convert categories into numerical values.

## Conclusion

This project demonstrates how to clean, process, and analyze sales and customer data to gain insights into customer behaviors and improve business strategies. The data was cleaned and preprocessed to ensure its usability, and key features were engineered to better understand customer purchasing patterns. Exploratory Data Analysis (EDA) helped uncover meaningful insights into the distribution of customer ratings, age groups, and purchasing behaviors.

Through these steps, customer segments and trends were identified, which could be useful for future marketing strategies and targeted campaigns. While no predictive modeling was performed in this project, the data processing and analysis provide a strong foundation for any subsequent machine learning tasks.

For more details and to access the complete project, you can visit: [E-commerce Data Analysis Project](https://www.kaggle.com/code/fatmanurkantar/e-commerce-data-analysis)


