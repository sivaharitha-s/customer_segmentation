K-Means Clustering on Mall Customers Dataset

Introduction

This project performs K-Means clustering on the Mall Customers dataset to segment customers based on their spending behavior and annual income.

Libraries Used

    =>pandas

    =>sklearn.cluster (KMeans)

    =>matplotlib.pyplot

    =>seaborn

Steps Involved

    =>Load Dataset

    =>Read the dataset using pandas.

    =>Display the first few records using df.head().

Data Visualization

     =>Scatter plot of Annual Income (k$) vs. Spending Score (1-100).

     =>Finding Optimal Number of Clusters (Elbow Method)

     =>Compute Within-Cluster Sum of Squares (WCSS) for different cluster counts.

     =>Plot WCSS values to determine the elbow point.

     =>Apply K-Means Clustering

     =>Use KMeans with n_clusters=5.

     =>Predict cluster labels and store them in the dataset.

    =>Visualizing Clusters

     =>Plot clusters using different colors.

      =>Mark centroids using kmeans.cluster_centers_.

      =>Clustering Based on Multiple Features

      =>Encode categorical variables (Gender).

      =>Apply KMeans to Age, Annual Income (k$), and Spending Score (1-100).

      =>Visualize clusters.

Results

The dataset is successfully segmented into customer clusters.

Elbow Method helped determine the optimal number of clusters.

K-Means clustering provided meaningful customer groups based on spending habits and income levels.
