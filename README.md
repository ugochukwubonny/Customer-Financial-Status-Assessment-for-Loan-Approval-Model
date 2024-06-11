# Customer-Financial-Status-Assessment-for-Loan-Approval-Model

## Project Overview
This project aims to assess the financial status of customers who have applied for loans at Interswitch, with the goal of determining which customers are eligible for loan approval. The assessment is based on two main criteria:

## Customers who are verified.
Customers with a credit score above 700.
We use a K-Means clustering model to group customers based on their financial attributes, helping stakeholders understand the financial profiles of potential loan applicants.

## Dataset
The dataset used for this project includes various financial attributes of customers. Key features might include (but are not limited to):

Verification status
Credit score
Income
Debt-to-income ratio
Number of open credit lines
Loan amount requested
Other relevant financial metrics
Packages Used
The following Python packages were used in this project:

pandas: For data manipulation and analysis.
matplotlib.pyplot: For plotting and visualizing data.
seaborn: For advanced visualizations.
sklearn.cluster.KMeans: For implementing the K-Means clustering algorithm.
sklearn.metrics.silhouette_score: For evaluating the quality of the clustering.
warnings: To handle and ignore warnings.
Exploratory Data Analysis (EDA)
Prior to building the K-Means model, an exploratory data analysis (EDA) was conducted to:

Understand the distribution of financial attributes.
Identify any missing or anomalous data points.
Visualize relationships between different financial metrics.
Ensure that only verified users with a credit score above 700 are included in the analysis.
Model Building
The K-Means clustering algorithm was chosen for this project to group customers into clusters based on their financial attributes. The steps involved in building the model include:

## Data Preprocessing
Filtering Data: Ensuring that only verified users with a credit score above 700 are included.
Normalization: Scaling the data to ensure that all financial attributes contribute equally to the clustering.

## Implementing K-Means
Choosing the Number of Clusters: Using the Elbow method and Silhouette score to determine the optimal number of clusters.
Fitting the Model: Applying the K-Means algorithm to the preprocessed data.
Evaluating the Model: Using metrics like Silhouette score to evaluate the quality of the clustering.

## Results
Optimal Clusters: The optimal number of clusters was determined using the Elbow method and Silhouette score.
Cluster Analysis: Customers were grouped into clusters based on their financial attributes, providing insights into their financial status.
Silhouette Score: The Silhouette score was used to evaluate the clustering quality, indicating how well-separated the clusters are.

## Conclusion
The K-Means clustering model successfully grouped customers into distinct clusters based on their financial attributes, helping stakeholders at Interswitch identify customers eligible for loan approval. This model provides a valuable tool for assessing the financial status of potential loan applicants.

## Future Work
Feature Engineering: Incorporating additional financial metrics and demographic information to improve clustering accuracy.
Model Refinement: Experimenting with other clustering algorithms and tuning model parameters for better performance.
Deployment: Integrating the model into a real-time loan approval system for automated assessment.
