# Segmentation-of-Adults

This project explores hidden patterns in the different groups of adults in society using unsupervised learning. By applying k-means clustering to the Adult dataset (from the UCI Machine Learning Repository), we uncover latent socioeconomic groups without using income as a label. Our analysis segments the adult population into distinct clusters based on demographic, educational, and employment features, and later relates them to income levels to assess socioeconomic stratification.

## Research Question
> **1. What distinct groups of adults exist in the dataset based on their demographic, educational, and work characteristics?**
>
> **2. What are the income status of these groups of adults?**

Understanding these segments can provide insight for:

- Policy-makers designing programs for different population groups
- Businesses targeting customers with tailored services
- Data scientists looking to engineer informative group-level features for supervised learning

## Tools
- Python
- scikit-learn: k-means, preprocessing, PCA
- pandas: data wrangling
- matplotlib / seaborn: visualization/EDA
- One-hot encoding and standardization for feature preprocessing
- Elbow method to select the optimal number of clusters
- PCA for 2D cluster visualization


## Project Structure
1. Data Loading and Cleaning
2. Exploratory Data Analysis (EDA)
3. Elbow Method to Determine Optimal k
4. Fit Final Model and Assign Clusters
5. Cluster Interpretation
6. PCA Visualization
7. Compare Cluster Distribution with Income to Assess Socioeconomic Patterns
8. Analyze Clustering Performance
9. Conclusion and Insights

## Acknowledgements/Reference
This dataset is found in the UCI machine learning repository
- https://archive.ics.uci.edu/dataset/2/adult
- https://www.cs.toronto.edu/~delve/data/adult/desc.html
There are also detailed description of the dataset in this link
- https://www.cs.toronto.edu/~delve/data/adult/adultDetail.html

