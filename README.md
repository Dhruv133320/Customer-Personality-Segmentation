# Customer-Personality-Segmentation
Customer Personality Segmentation using K-Means and Hierarchical Clustering with Python.
# Customer Personality Segmentation using Clustering

## Overview

This project explores customer personality data using **unsupervised machine learning** techniques to identify meaningful customer segments. The analysis includes data preprocessing, exploratory data analysis (EDA), K-Means Clustering, Hierarchical Clustering, and cluster evaluation.

The objective is to group customers with similar characteristics, helping businesses better understand customer behavior and support data-driven marketing strategies.

---

## Features

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- K-Means Clustering
- Elbow Method for selecting the optimal number of clusters
- Hierarchical (Agglomerative) Clustering
- Dendrogram visualization
- Silhouette Score evaluation
- Cluster prediction and centroid analysis

---

## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- SciPy

---

## Project Workflow

```
Dataset
   │
   ▼
Data Cleaning
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Feature Selection
   │
   ▼
K-Means Clustering
   │
   ▼
Elbow Method
   │
   ▼
Hierarchical Clustering
   │
   ▼
Silhouette Score Evaluation
   │
   ▼
Customer Segmentation
```

---

## Project Structure

```
customer-personality-segmentation/
│
├── notebook.ipynb
├── README.md
├── requirements.txt
├── dataset/
│   └── customer_personality.csv
├── images/
└── LICENSE
```

---

## Results

This project successfully:

- Performed customer segmentation using K-Means Clustering.
- Applied Hierarchical Clustering for comparison.
- Determined an appropriate number of clusters using the Elbow Method.
- Evaluated clustering quality using the Silhouette Score.
- Visualized hierarchical relationships through a dendrogram.

These techniques demonstrate how unsupervised learning can uncover hidden patterns within customer data.

---

## Future Improvements

- Perform Principal Component Analysis (PCA) for cluster visualization.
- Compare results with DBSCAN.
- Build an interactive dashboard using Tableau or Power BI.
- Deploy the project as a web application.

---

## Getting Started

Clone the repository:

```bash
git clone https://github.com/your-username/customer-personality-segmentation.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook and open the project notebook.

---

## Author

**Dhruv Borija**



## License

This project is licensed under the MIT License.
