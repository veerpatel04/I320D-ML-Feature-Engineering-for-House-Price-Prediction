# I320D ML-Feature Engineering for House Price Prediction

Dataset: https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/overview

## Project Overview:
This project revolves around the exploration and application of feature engineering techniques to improve the quality of a given real estate dataset. The dataset, provided in CSV format, encompasses various features related to properties, such as lot shape, configuration, neighborhood, overall quality, and sale prices. The primary objective is to get more hands-on experience in data loading, exploratory data analysis (EDA), feature and label definition, feature transformation, and potentially feature scaling.

## Introduction:
The primary focus is on feature engineering, a pivotal component of machine learning and data analysis. Feature engineering involves selecting, transforming, and creating new features to enhance machine learning model performance. This project gave me an opportunity to engage in tasks such as loading datasets, conducting exploratory data analysis, defining features and labels, transforming categorical features, and potentially scaling numerical features.

## Tasks:
In the initial task, I loaded the dataset using Pandas and inspect a few rows to understand the available features. The subsequent task involves exploratory data analysis (EDA) to identify and address duplicate rows, check data types, and ensure data integrity. Feature and label definition tasks include removing incomplete rows, selecting features and labels, and creating distinct DataFrames for housing features and sale prices. I then transformed categorical features into one-hot encodings and potentially scale numerical features. 

## Insights:
Identifying and eliminating duplicate rows is pivotal for data integrity. However, a high count may indicate potential errors during data collection. In feature definition, the removal of rows with NULL entries is crucial for completeness, but extensive removals may impact the available data. Feature transformation involves one-hot encoding categorical features.

## Issues Observed:
In EDA, printing the entire dataset information may be overwhelming with numerous columns. When defining features, a small dataset post-removals may impact machine learning model performance. Feature transformation, particularly one-hot encoding, can substantially increase column count, affecting model training time. For feature scaling, not all features or models require scaling, dependent on the algorithm used.

