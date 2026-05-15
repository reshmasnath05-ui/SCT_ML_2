# SCT_ML_2

# Customer Segmentation using K-Means Clustering

![Project Banner](images/project_summary.png)

## Overview
This project performs customer segmentation using the K-Means Clustering algorithm. Customers are grouped based on their **Annual Income** and **Spending Score** to identify meaningful purchasing behavior patterns.

---

## Features
- Data preprocessing and visualization
- Elbow Method to determine optimal clusters
- K-Means clustering implementation
- Cluster visualization and centroid analysis

---

## Dataset
Mall Customers Dataset

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

---

# Results

## 1. Customer Segmentation

![Customer Segmentation](images/cluster_visualization.png)

Customers were successfully segmented into **5 distinct groups** based on their spending behavior and annual income.

---

## 2. Cluster Centers

![Cluster Centers](images/cluster_centers.png)

The black X marks represent the centroids of each customer cluster.

---

## 3. Elbow Method

![Elbow Method](images/elbow_method.png)

The Elbow Method was used to determine the optimal number of clusters (**K = 5**).

---

# Project Structure

```bash
SCT_ML_2/
│── data/
│   └── Mall_Customers.csv
│
│── notebooks/
│   └── TASK-2-KMeans-Clustering.ipynb
│
│── images/
│   ├── cluster_visualization.png
│   ├── cluster_centers.png
│   ├── elbow_method.png
│   └── project_summary.png
│
│── README.md
│── requirements.txt
│── LICENSE
│── .gitignore
