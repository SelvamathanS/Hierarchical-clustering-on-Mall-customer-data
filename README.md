# Hierarchical Clustering on Mall Customer Data

A machine learning project demonstrating **Hierarchical Clustering** on the classic *Mall Customers* dataset using Python and Jupyter Notebook.

Hierarchical clustering is an unsupervised clustering technique used to group similar data points into a hierarchy of clusters, often visualized using a dendrogram. This project shows how to use hierarchical clustering to segment mall customers based on their annual income and spending score.

## Project Overview

This repository contains a Jupyter Notebook that:

- Loads and explores the *Mall Customers* dataset.
- Prepares relevant features for clustering.
- Applies hierarchical clustering (Agglomerative Clustering).
- Uses a dendrogram to find the optimal number of clusters.
- Visualizes resulting customer segments in a scatter plot.

The goal is to identify meaningful groups of mall customers based on their spending behavior and income.

### 1. Clone the Repository

```bash
git clone https://github.com/SelvamathanS/Hierarchical-clustering-on-Mall-customer-data.git
cd Hierarchical-clustering-on-Mall-customer-data
````

### 2. Install Dependencies

Make sure you have Python 3.x installed. Then install required packages:

```bash
pip install -r requirements.txt
```

If you don’t have a `requirements.txt`, you can install typical ML libraries:

```bash
pip install numpy pandas matplotlib scipy scikit-learn
```

### 3. Run the Notebook

Open the Jupyter notebook:

```bash
jupyter notebook Hierarchical_clustering.ipynb
```

Then run the cells to explore the analysis and clustering results.

## 📈 What You’ll See in the Notebook

The notebook will walk you through:

1. **Importing necessary libraries**
2. **Loading the data**
3. **Feature selection** — typically selecting *Annual Income* and *Spending Score*
4. **Dendrogram analysis** to determine optimal cluster count
5. **Applying Agglomerative Hierarchical Clustering**
6. **Visualizing clusters**

## 🧩 Results & Insights

By running the notebook, you will be able to observe:

* A **dendrogram** that visualizes how clusters merge at different distances.
* A scatterplot showing customers grouped into clusters based on spending and income.
* Insights into customer behavior and segmentation.
