# Iris-Clustering-Project

This project demonstrates clustering techniques using the Iris dataset. The clustering algorithms applied are:

1. **KMeans Clustering**
2. **Hierarchical Clustering**

## Dataset

The Iris dataset contains the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width

The target (species) column is dropped, and the clustering is performed based on the feature set.

## Preprocessing steps
1. Dropping the target column since it's a clustering problem.
2. Removed Duplicates values.
3. Created a histogram and box plot for visualization.
4. Standardize the dataset using StandardScaler.

## Algorithms Used

### KMeans Clustering
- KMeans is an iterative, partitional clustering algorithm.
- The dataset was clustered into 3 groups corresponding to the Iris species.
- Visualized the clusters using a scatter plot.

### Hierarchical Clustering
- An agglomerative clustering technique that builds a hierarchy of clusters.
- The dataset was clustered into 3 groups.
- A dendrogram was created to visualize the merging process of the clusters.
