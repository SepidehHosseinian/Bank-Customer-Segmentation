# Bank-Customer-Segmentation

This repository contains the code and data for a machine learning project on bank customer segmentation. The goal of this project is to use clustering techniques to segment the bank customers into different groups based on their demographic and behavioral characteristics. The project also aims to analyze and visualize the clusters and identify the key features that distinguish them.

## Data
The data used for this project is the [Bank Marketing Data Set] from the UCI Machine Learning Repository. The data set contains information about 41,188 customers of a Portuguese bank who were contacted by phone for a marketing campaign. The data set has 20 input variables, such as age, job, marital status, education, balance, etc., and one output variable, which is the response to the campaign (yes or no).

## Code
The code for this project is written in Python and uses the following libraries:

•  pandas

•  numpy

•  matplotlib

•  seaborn

•  scikit-learn

### The code consists of four main steps:

•  Data exploration and preprocessing: This step involves loading, cleaning, and transforming the data, as well as performing some exploratory data analysis and visualization.

•  Feature engineering and selection: This step involves creating new features or transforming existing ones to enhance their predictive power and relevance, as well as selecting the most important or relevant features from the available ones.

•  Model training and evaluation: This step involves applying different clustering algorithms, such as K-Means, Hierarchical Clustering, and DBSCAN, to segment the customers into different groups, as well as evaluating the quality and validity of the clusters using various metrics and techniques, such as silhouette score, elbow method, etc.

•  Cluster analysis and visualization: This step involves analyzing and visualizing the clusters and identifying the key features that characterize them, as well as providing some insights and recommendations for the bank's marketing strategy.

The code is organized in a Jupyter notebook file named bank_customer_segmentation.ipynb, which contains detailed explanations and comments for each step.

## Results
The results of this project show that the bank customers can be segmented into four distinct groups based on their demographic and behavioral characteristics:

•  Cluster 0: This group consists of young, single, educated customers who have high income and balance, but low response rate to the campaign. They are likely to be professionals or entrepreneurs who are busy and not interested in the bank's product.

•  Cluster 1: This group consists of old, married, retired customers who have low income and balance, but high response rate to the campaign. They are likely to be loyal and satisfied customers who are looking for long-term investments or savings.

•  Cluster 2: This group consists of middle-aged, married, blue-collar customers who have moderate income and balance, but low response rate to the campaign. They are likely to be workers or employees who are stable and conservative in their financial decisions.

•  Cluster 3: This group consists of young, single, students or unemployed customers who have low income and balance, but high response rate to the campaign. They are likely to be adventurous and curious customers who are looking for new opportunities or challenges.

The results also show that the most important features that distinguish the clusters are age, marital status, job, education, balance, and response.

The results can help the bank improve its marketing strategy by targeting different segments of customers with different offers and messages that suit their needs and preferences.

## References
: Bank Marketing Data Set
