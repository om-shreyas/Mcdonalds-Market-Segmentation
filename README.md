# Mcdonalds-Market-Segmentatio
This project explores various aspects of a dataset related to preferences for McDonald's food items. It involves data preprocessing, exploratory data analysis (EDA), dimensionality reduction using Principal Component Analysis (PCA), and K-means clustering for segmentation.

## Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Principal Component Analysis (PCA)](#principal-component-analysis)
- [K-means Clustering](#k-means-clustering)
- [Segment Profiling](#segment-profiling)
- [Decision Tree Classifier](#decision-tree-classifier)
- [Conclusion](#conclusion)

## Project Overview
In this project, we analyze a dataset containing preferences and characteristics of individuals related to McDonald's food items. The primary objectives of this project are as follows:

1. **Data Preprocessing**: Perform data preprocessing tasks such as data cleaning and encoding categorical variables.

2. **Exploratory Data Analysis (EDA)**: Explore the dataset to understand its structure and characteristics.

3. **Principal Component Analysis (PCA)**: Apply PCA to reduce the dimensionality of the dataset and visualize the data in lower dimensions.

4. **K-means Clustering**: Implement K-means clustering to segment the dataset into distinct clusters based on preferences and characteristics.

5. **Segment Profiling**: Profile the segments to gain insights into the preferences and characteristics of each group.

6. **Decision Tree Classifier**: Use a decision tree classifier to predict the cluster segment based on various features.

## Dataset
The dataset used in this project contains the following columns:

- `yummy`: Whether the food item is considered yummy (Yes/No)
- `convenient`: Whether the food item is considered convenient (Yes/No)
- `spicy`: Whether the food item is considered spicy (Yes/No)
- `fattening`: Whether the food item is considered fattening (Yes/No)
- `greasy`: Whether the food item is considered greasy (Yes/No)
- `fast`: Whether the food item is considered fast (Yes/No)
- `cheap`: Whether the food item is considered cheap (Yes/No)
- `tasty`: Whether the food item is considered tasty (Yes/No)
- `expensive`: Whether the food item is considered expensive (Yes/No)
- `healthy`: Whether the food item is considered healthy (Yes/No)
- `disgusting`: Whether the food item is considered disgusting (Yes/No)
- `Like`: Likeness score ranging from -5 (Hate it) to 5 (Love it)
- `Age`: Age of the individual
- `VisitFrequency`: Frequency of visits to McDonald's
- `Gender`: Gender of the individual (Male/Female)

## Exploratory Data Analysis
The exploratory data analysis (EDA) phase includes examining the dataset's basic statistics, identifying unique values in categorical columns, and visualizing correlations between variables. Key observations include the mean Likeness score and age distribution.

## Principal Component Analysis (PCA)
PCA is applied to reduce the dimensionality of the dataset while preserving as much information as possible. The reduced dataset is then analyzed using scatterplots.

## K-means Clustering
K-means clustering is performed to segment the dataset into distinct groups. The Elbow method and Silhouette score are used to determine the optimal number of clusters. Four clusters are identified as suitable for this dataset.

## Segment Profiling
Profiles for each cluster are created, showing the average values for each attribute within each segment. Key attributes include "Like," "Age," and "VisitFrequency." Scatterplots and bar plots are used for visualization.

## Decision Tree Classifier
A decision tree classifier is trained to predict the cluster segment based on various features. The decision tree is visualized to understand the classification process.

## Conclusion
This project provides insights into customer preferences and characteristics related to McDonald's food items. It segments customers into four distinct clusters and profiles each segment. The decision tree classifier allows for predicting cluster segments based on individual characteristics.

Please refer to the Jupyter Notebook or script for detailed code and visualizations related to this project.