Mini Project: Customer Segmentation using K-Means Clustering
# Objective:

 To segment customers into distinct groups based on their purchasing behavior, using clustering algorithms for better marketing strategies and customer 
 targeting.

# Dataset Used:

 [Mall Customer Dataset] (typically includes features like Age, Annual Income, and Spending Score)

## Tools & Technologies:

 Python
 Jupyter Notebook
 Libraries: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Key Steps:

 #Data Exploration & Preprocessing:

 Loaded and cleaned the data.
 Explored distributions of customer attributes (e.g., Age, Income).
 Handled missing values and scaled features where necessary.

# Feature Selection:

 Chose relevant features: Annual Income and Spending Score.
 Created 2D and 3D plots to visualize customer distribution.

# Finding Optimal Clusters (Elbow Method):
 
 Used the Elbow Method to determine the optimal number of clusters (K).
 Identified the best K value (commonly K=5) where the within-cluster sum of squares (WCSS) showed diminishing returns.
 
# Clustering using K-Means:

 Applied K-Means algorithm with the optimal K.
 Assigned each customer to a segment.
 Visualized the clusters in a scatter plot with distinct colors.

# Insights:
 
 Segmented customers into groups such as:
 High spenders with high income
 Budget-conscious customers
 Average spenders with moderate income
 These insights can help businesses tailor marketing strategies.
