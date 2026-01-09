# clustering


# Clustering the Iris Dataset

### Unsupervised Machine Learning Assessment

## Project Overview

This project demonstrates the application of unsupervised learning techniques on the **Iris Dataset**. The goal is to group iris flowers into clusters based on their morphological measurements (sepal length, sepal width, petal length, and petal width) without using predefined labels.

##  Technologies Used

* **Language:** Python 3.x
* **Libraries:** * `pandas` & `numpy` (Data manipulation)
* `matplotlib` & `seaborn` (Data visualization)
* `scikit-learn` (KMeans implementation)
* `scipy` (Hierarchical linkage and dendrograms)


##  Algorithms Implemented

### 1. KMeans Clustering

KMeans is a partition-based algorithm that groups data into  clusters by minimizing the distance between data points and the cluster centroid.

* **Why Iris?** The dataset features are continuous and relatively well-separated, making it ideal for centroid-based grouping.

### 2. Hierarchical Clustering (Agglomerative)

This is a bottom-up approach where each observation starts in its own cluster, and pairs of clusters are merged as one moves up the hierarchy.

* **Why Iris?** It allows for the visualization of a **Dendrogram**, which helps in understanding the taxonomic relationships between different flower samples.

---

## Dataset Details

The Iris dataset consists of 150 samples from three species of Iris (*Iris setosa*, *Iris virginica*, and *Iris versicolor*).
**Note:** For this assessment, the target species labels were dropped to treat the task as a pure clustering problem.



##  Results Summary

* **KMeans** successfully identified three distinct clusters, though some overlap exists between *Versicolor* and *Virginica*.
* **Hierarchical Clustering** provided a clear dendrogram that suggests three main branches, aligning with the biological reality of the dataset.

