# AIM-Capstone-Project---Lumain
A repository of files needed for the AIM Capstone Project

Source File: "E-Commerce Transaction" from Kaggle retrieved via: https://www.kaggle.com/datasets/gabrielramos87/an-online-shop-business

**Problem Statement**
Modern e-commerce platforms handle large volumes of transactional data across various geographical regions, but often fail to leverage this data for targeted marketing and customer retention. Traditional one-size-fits-all marketing campaigns yield low conversion rates and inefficient marketing expenditure.

The objective of this project is to build an end-to-end data science framework to:
1. Segment Customers: Group customers dynamically based on historical transactional behavior (Recency, Frequency, Monetary value) and temporal purchase habits.
2. Predict Product Affinity & Activation: Scientifically determine which product categories each customer segment is most likely to purchase next, enabling hyper-personalized marketing campaigns and activation strategies.
3. Analyze Seasonality & Timing: Identify key purchasing windows, peak transaction times, and seasonal trends across categorized product items and purchase volumes.
4. Evaluate Geographic & Cultural Context: Assess how country of origin impacts spending behavior, product category preference, and purchase timing.

**Methodology**
To address these business goals, the project uses a hybrid machine learning pipeline:
1. Primary Task — Unsupervised Learning (Clustering): Partitioning the customer base into distinct behavioral personas using algorithms such as K-Means, Agglomerative Hierarchical Clustering, or DBSCAN.
2. Secondary Task — Recommendation / Market Basket Analysis

**Business Success Metrics**
1. Transaction volume & value (in absolute value and in growth rates)
2. Customer Lifetime Value (CLV) Uplift: Projected increase in revenue per customer post-segmentation.
3. Campaign Conversion Rate: Increase in response rate to targeted product activation offers vs. generic broad offers.
4. Repeat Purchase / Retention Rate: Percentage increase in returning customers over seasonal cycles.
