# World Happiness Report Clustering Using the KDD Process and DBSCAN

This project applies the **KDD (Knowledge Discovery in Databases)** process to the **World Happiness Report** dataset, clustering countries based on happiness indicators such as **GDP per capita**, **social support**, and **life expectancy**. The **DBSCAN (Density-Based Spatial Clustering of Applications with Noise)** algorithm is used to identify clusters and outliers, allowing us to discover patterns in global happiness trends.

## Project Overview

The primary goal of this project is to cluster countries using DBSCAN based on their happiness indicators and analyze the patterns that emerge. By following the KDD process, we move through steps of data cleaning, transformation, and mining to uncover meaningful insights from the dataset.

### Key Features:
- **Data Cleaning**: Preprocessing the dataset to handle missing values and noise.
- **Data Transformation**: Standardizing the data to ensure fairness in the clustering process.
- **Clustering with DBSCAN**: Identifying well-defined clusters of countries and detecting outliers that deviate from the norm.
- **Pattern Evaluation**: Using the Silhouette Score to evaluate the clustering quality.
- **Visualization**: Visualizing the clusters in a 2D space using PCA for better interpretability.

![image](https://github.com/user-attachments/assets/e6119657-024d-4107-ac36-aad51f355e72)


## Links

- **Colab Notebook**: You can find the full implementation of the project in this [Colab Notebook](https://colab.research.google.com/drive/1FI9JrIScuVvHJAgDQ2s6Qwyl9KnZFamY).
  
- **Medium Article**: For a detailed walkthrough of the project, including explanations of each step in the KDD process, check out the [Medium Article](https://medium.com/@apurva.karne/unveiling-clusters-in-the-world-happiness-report-using-the-kdd-process-and-dbscan-b337730e20bc).

## Steps in the KDD Process

1. **Business Understanding**: Understanding the objective and how happiness indicators can help uncover patterns across countries.
2. **Data Understanding**: Exploring and visualizing the data to get a clear picture of the happiness distribution across nations.
3. **Data Preparation**: Cleaning the data, handling missing values, and preparing it for analysis.
4. **Modeling (DBSCAN)**: Applying DBSCAN to detect natural clusters of countries based on happiness indicators.
5. **Evaluation**: Assessing the clustering using metrics like the Silhouette Score to ensure meaningful separation between clusters.
6. **Deployment**: Visualizing the clusters using PCA to project the high-dimensional data into a two-dimensional space for easier interpretation.

---

### Author
**Apurva Karne**

If you found this project useful, feel free to star this repository and follow me on [Medium](https://medium.com/@apurva.karne) for more content related to data science and machine learning.
