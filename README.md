Campaign Analysis and Customer Association Rules

Overview

This project consists of two main components:

Campaign Analysis: Data cleaning, visualization, and exploring relationships between different customer attributes.

Association Rules Mining: Finding frequent patterns and customer associations using the Apriori algorithm to predict response behavior and cluster customers into five groups.

Features

1. Campaign Analysis

Data Cleaning: Handle missing values, normalize data, and prepare the dataset for analysis.

Exploratory Data Analysis (EDA):

Visualizing key trends and patterns.

Understanding the distribution of customer attributes.

Examining correlations between features such as age, income, and response rate.

2. Finding Association Rules

Association Rule Mining:

Using the Apriori algorithm to identify frequent patterns in customer behavior.

Determining which factors influence customer response.

Customer Segmentation:

Clustering customers into five distinct groups based on their behaviors and response likelihood.

Installation

Ensure you have the required dependencies installed:

pip install pandas numpy matplotlib seaborn mlxtend

Usage

Run the campaign analysis script to explore and visualize data:

python campaign_analysis.py

Run the association rules script to extract insights and cluster customers:

python association_rules.py

Results

Identified key customer attributes that influence campaign response.

Discovered frequent patterns among customer groups.

Clustered customers into five segments based on association rules.

Future Improvements

Test different clustering methods (e.g., K-Means, DBSCAN) for better segmentation.

Apply deep learning for customer response prediction.

License

This project is open-source and available under the MIT License.
