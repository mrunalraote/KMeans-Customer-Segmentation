# KMeans – Customer Segmentation

## Objective
To perform customer segmentation using KMeans clustering and identify distinct customer groups based on purchasing behavior.

## Dataset
- Mall Customer Segmentation Dataset (Kaggle)
- Features used:
  - Annual Income (k$)
  - Spending Score (1–100)

## Tools & Technologies
- Python
- Scikit-learn
- Matplotlib

## Approach
1. Loaded and explored the mall customer dataset.
2. Removed the CustomerID column as it does not contribute to clustering.
3. Applied StandardScaler to normalize feature values.
4. Used the Elbow Method to determine the optimal number of clusters.
5. Trained the KMeans model with the selected number of clusters.
6. Assigned cluster labels to each customer.
7. Visualized customer segments using scatter plots.
8. Saved the segmented dataset for further analysis.

## Deliverables
- Elbow Plot for optimal K selection
- Cluster Visualization Plot
- Segmented Dataset CSV file

## Results
- Customers were grouped into meaningful clusters based on income and spending behavior.
- Each cluster represents a distinct customer segment useful for business decision-making.

## Learning Outcome
This task helped understand unsupervised learning, distance-based clustering, feature scaling importance, and practical customer segmentation for marketing and business insights.

## Files
- `kmeans_customer_segmentation.ipynb`
##Author
Mrunal Arote
- `Mall_Customers.csv`
- `segmented_customers.csv`
