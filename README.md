Project Overview
Importing Necessary Libraries: The project utilizes various libraries including numpy, pandas, matplotlib, and scikit-learn.

Separating Features and Labels: The dataset is split into features (X) and labels (y).

Standardizing the Data: The feature data is standardized to ensure consistency in the analysis.

Dimensionality Reduction Using PCA: PCA is applied to reduce the data to 2 dimensions for easier visualization.

Determining Optimal Number of Clusters:

Elbow Method: Used to identify the optimal number of clusters by plotting the within-cluster sum of squares (WCSS).
Silhouette Score Method: Evaluated the quality of clustering by measuring how well each data point is clustered relative to others, suggesting 2 clusters as optimal.
Applying K-means Clustering: K-means clustering is applied to the PCA-transformed data, and cluster assignments are predicted.

Visualizing the Clusters: The clusters are visualized by plotting the PCA-reduced data and marking the cluster centers.

Dependencies
numpy
pandas
matplotlib
scikit-learn
Running the Code
Ensure all necessary libraries are installed.
