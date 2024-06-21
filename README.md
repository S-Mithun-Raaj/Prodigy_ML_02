# Customer Segmentation using K-means Clustering Project
    This project utilizes Python along with pandas and matplotlib to perform customer segmentation using K-means clustering.

# Dataset Overview
    The dataset used in this project is from a mall and contains the following features:

  ### Age: 
        Age of the customers
  ### Gender: 
        Binary valued (Male/Female)
  ### Annual Income: 
        Annual income of the customers
  ### Spending Score: 
        Spending score assigned to the customers based on their spending behavior
# Project Steps
## Data Preprocessing
        Checked for null values in the dataset.
        Analyzed the distribution of features.

# Determining Optimal K
        Utilized the elbow method and within-cluster sum of squares (WCSS) to determine the optimal number of clusters (K=5).
# Model Training
## Trained two K-means clustering models:
        First model using all three features: Gender, Annual Income, and Spending Score.
        Second model using only Annual Income and Spending Score.
# Model Evaluation
Visualized the results of both models using scatter plots to understand customer segments.
Evaluated the inertia of both models.
The model with only Annual Income and Spending Score showed lower inertia, indicating it as the better model for segmentation.
# Conclusion
This project demonstrates the use of K-means clustering for customer segmentation based on mall data. By comparing different models, it was found that using Annual Income and Spending Score provides a clearer segmentation of customers.
