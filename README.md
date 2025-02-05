# Clustering Analysis Assignment

This project is a comparative performance study of different clustering algorithms using various preprocessing techniques. The assignment includes implementing clustering on a dataset, analyzing results with visualizations, and summarizing the findings. The results are saved and described for presentation and further analysis.

## Objectives

1.Perform clustering using different algorithms (e.g., K-Means, DBSCAN, Mean Shift) on a dataset.

2.Apply multiple preprocessing techniques like normalization, transformations, and PCA.

3.Evaluate clustering performance using metrics such as:

a.Silhouette Score

b.Calinski-Harabasz Index

c.Davies-Bouldin Index

4.Visualize clustering results with detailed plots.

## Dataset

The dataset used for this analysis was sourced from the UCI Machine Learning Repository. PCA is applied to reduce dimensionality for visualization and performance enhancement.
## Preprocessing Techniques

No Processing: Original dataset without preprocessing.

Normalization: Scaling the data to a range of [0, 1].

Transformations: Applying transformations like logarithmic or square root for variance stabilization.

PCA: Dimensionality reduction using Principal Component Analysis.

Combination (T+N, T+N+PCA): Combining transformations and PCA.

## Clustering Algorithms

K-Means Clustering

Hierarchical Clustering

DBSCAN

Mean Shift Clustering

## Evaluation Metrics

Silhouette Score: Measures how similar an object is to its own cluster compared to other clusters.

Calinski-Harabasz Index: Higher values indicate better-defined clusters.

Davies-Bouldin Index: Lower values indicate better clustering.

## Visualizations

The analysis includes the following visualizations:

a.Scatter Plot with Clusters: PCA visualization of clustered data.

b.Elbow Method: To identify the optimal number of clusters.

c.Silhouette Analysis: To evaluate the quality of clusters.

d.Cluster Heatmap: Cluster-wise comparison of feature means.

## Results

The comparative study shows how different preprocessing techniques and clustering algorithms perform on the dataset. Results are summarized in a table format showing performance metrics (e.g., Silhouette Score, Calinski-Harabasz Index, Davies-Bouldin Index).
![image](https://github.com/user-attachments/assets/482bf949-5b20-446d-93f6-2e44b0c85e5c)

![image](https://github.com/user-attachments/assets/ec170cd1-3412-4978-9f2b-4ebd7938ba08)

![image](https://github.com/user-attachments/assets/05559cc0-af58-478d-9edf-0bcb22619824)

## Graphs 


![image](https://github.com/user-attachments/assets/c76e8437-5bdd-436a-be3b-2b46ea4649bc)


![image](https://github.com/user-attachments/assets/4c53a66a-4729-416a-9580-b86b22049b9a)

![image](https://github.com/user-attachments/assets/aa8eeed9-a8ce-4a4e-8684-031268fddbec)

![image](https://github.com/user-attachments/assets/c8d1fad2-422d-4a50-a44d-54a7c880bc9d)


## Conclusion

Conclusion

This project highlights the impact of preprocessing techniques on clustering performance. It provides a framework for evaluating and visualizing clustering results using multiple algorithms and metrics.





