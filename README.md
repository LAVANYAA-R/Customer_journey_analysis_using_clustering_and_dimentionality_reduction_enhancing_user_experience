# Customer_journey_analysis_using_clustering_and_dimentionality_reduction_enhancing_user_experience
Project Overview
This project focuses on analyzing customer behavior throughout their purchasing journey. It involves data preprocessing, visualization, and clustering techniques to segment customers based on their engagement levels. By leveraging machine learning, the project aims to extract meaningful insights that can help businesses optimize their marketing and sales strategies.

Key Components
Data Collection & Preprocessing

The dataset contains information about customer interactions on a travel-related website.
Features include yearly average views on travel pages, yearly comments, and product purchases.
Data preprocessing involves handling missing values, normalizing numerical features using StandardScaler, and encoding categorical variables using OneHotEncoder.
Customer Journey Funnel Analysis

The project identifies key stages in the customer journey:
Viewing the travel page
Commenting on the travel page
Purchasing a product
It calculates the percentage of users at each stage and visualizes the drop-off rate using funnel plots.
Clustering Customers

K-Means Clustering: Segments customers into groups based on engagement patterns.
Hierarchical Clustering: Provides insights into how customers relate to each other.
The goal is to identify high-value customers, casual browsers, and those likely to convert.
Dimensionality Reduction

Principal Component Analysis (PCA) is applied to reduce the number of features while retaining significant variance.
This helps in improving the efficiency of clustering and visualization.
Visualizing Insights

Bar charts and box plots showcase how different customer segments behave.
Scatter plots (using PCA) help in understanding cluster distributions.
Business Impact
Helps businesses target the right audience with personalized marketing.
Identifies potential churners who need re-engagement strategies.
Enhances conversion rates by optimizing website engagement.
