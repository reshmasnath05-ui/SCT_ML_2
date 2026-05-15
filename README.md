# SCT_ML_2


# Customer Segmentation using K-Means Clustering

## Overview
This project performs Customer Segmentation using the K-Means Clustering algorithm. The goal is to group customers based on their Annual Income and Spending Score to identify meaningful purchasing patterns and business insights.

---

## Objective
- Segment customers into different groups based on purchasing behavior
- Analyze customer spending habits
- Help businesses improve targeted marketing strategies

---

## Features
- Data preprocessing and exploration
- Elbow Method for optimal cluster selection
- K-Means clustering implementation
- Cluster visualization and centroid analysis
- Business insight generation from customer segments

---

## Dataset
The project uses the **Mall Customers Dataset**, which contains:
- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1–100)

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

---

## Project Structure

```bash
SCT_ML_2/
│── data/
│   └── mall_customers.csv
│
│── notebooks/
│   └── customer_segmentation_kmeans.ipynb
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
```

---

## Methodology

### 1. Data Preprocessing
- Imported dataset
- Selected relevant features
- Checked for missing values

### 2. Finding Optimal Clusters
The Elbow Method was used to determine the optimal number of clusters.

### 3. K-Means Clustering
Applied K-Means algorithm to segment customers into 5 distinct groups.

### 4. Visualization
Visualized:
- Customer clusters
- Cluster centroids
- Elbow curve

---

## Results
- Successfully segmented customers into 5 groups
- Identified customer spending patterns
- Generated insights useful for targeted marketing and customer engagement

---


## Future Improvements
- Deploy using Streamlit or Gradio
- Add interactive dashboards
- Use advanced clustering algorithms
- Perform deeper customer behavior analysis



