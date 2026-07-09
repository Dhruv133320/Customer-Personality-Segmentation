# Cardiac Arrest Risk Segmentation using Clustering

## Overview

This project applies **unsupervised machine learning** techniques to analyze cardiac health data and identify patient groups with similar characteristics. Using clustering algorithms, the project uncovers hidden patterns within the dataset that may assist in understanding different cardiac risk profiles.

The analysis includes data preprocessing, feature selection, K-Means Clustering, Hierarchical Clustering, and evaluation of clustering performance.

---

## Objectives

- Perform data preprocessing and cleaning
- Explore cardiac health data
- Apply K-Means Clustering to identify patient groups
- Determine the optimal number of clusters using the Elbow Method
- Compare results with Hierarchical Clustering
- Evaluate cluster quality using the Silhouette Score
- Visualize clustering results

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

## Dataset

The dataset contains patient health-related attributes that may contribute to cardiac arrest risk. These features are analyzed using clustering techniques to discover natural groupings without predefined labels.

---

## Project Workflow

```
Cardiac Health Dataset
          │
          ▼
Data Cleaning & Preprocessing
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
Patient Risk Segmentation
```

---

## Features

- Data preprocessing and cleaning
- Exploratory Data Analysis (EDA)
- K-Means Clustering
- Elbow Method for optimal cluster selection
- Hierarchical (Agglomerative) Clustering
- Dendrogram visualization
- Silhouette Score evaluation
- Cluster center analysis

---

## Results

This project successfully:

- Segmented patients into distinct groups based on cardiac health characteristics.
- Applied both K-Means and Hierarchical Clustering for comparative analysis.
- Used the Elbow Method to determine an appropriate number of clusters.
- Evaluated clustering performance using the Silhouette Score.
- Demonstrated the effectiveness of unsupervised learning in discovering meaningful patterns within healthcare data.

---


## Installation

Clone the repository:

```bash
git clone https://github.com/your-username/cardiac-arrest-clustering.git
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Run the Jupyter Notebook to explore the project.

---

## Future Improvements

- Apply Principal Component Analysis (PCA) for visualization.
- Compare with DBSCAN and Gaussian Mixture Models.
- Develop an interactive dashboard using Tableau or Power BI.
- Integrate predictive models for cardiac risk assessment.

---

## Author

**Dhruv Borija**

---

## License

This project is licensed under the MIT License.
