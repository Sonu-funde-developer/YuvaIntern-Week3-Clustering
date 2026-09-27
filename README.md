# YuvaIntern Week 3 - Unsupervised Learning and Clustering Analysis

## Project
Customer Segmentation Using K-Means Clustering on the Superstore dataset.

## Dataset
51,290 transaction rows and 4,873 unique customers.

## Features
- Total Sales
- Total Profit
- Total Quantity
- Number of Orders
- Average Order Value

## Method
StandardScaler + K-Means (k=4, random_state=42, n_init=20). Candidate k values 2-8 were evaluated using inertia and silhouette score.

## Improvements in this version
- Fully annotated visualizations with titles, axes, legends, and numerical labels where appropriate.
- Deeper cluster-by-cluster numerical interpretation.
- Specific comparison examples using calculated cluster metrics.
- Transparent explanation of why k=4 was selected even though another k had a higher silhouette score.
- Charts are embedded as outputs in the executed Jupyter Notebook.

## Files
- `Week3_Unsupervised_Learning_Clustering_Improved.ipynb`
- `YuvaIntern_Week3_Clustering_Improved_Report.docx`
- `data/superstore.csv`
- `output/customer_clusters.csv`
- `output/cluster_profile.csv`
- `output/k_selection_metrics.csv`
- `output/charts/`
