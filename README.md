# Customer Segmentation Using K-Means Clustering

## Project Objective

The objective of this project is to segment mall customers into different groups based on their purchasing behavior using unsupervised machine learning techniques.

Customer segmentation helps businesses understand customer patterns and create personalized marketing strategies to improve customer satisfaction, retention, and sales.

This project uses the Mall Customers Dataset and applies K-Means Clustering along with PCA/t-SNE visualization techniques to identify meaningful customer segments.

---

# Dataset Information

The dataset contains the following columns:

- CustomerID
- Genre
- Age
- Annual Income (k$)
- Spending Score (1-100)

### Dataset Description
- **Age** → Customer age
- **Annual Income (k$)** → Annual income in thousand dollars
- **Spending Score (1-100)** → Score assigned based on customer purchasing behavior
- **Genre** → Gender of customer

---

# My Approach

## 1. Data Loading and Preprocessing
- Loaded the dataset using Pandas
- Checked missing values and dataset information
- Removed unnecessary columns like `CustomerID`
- Encoded categorical features
- Standardized numerical data using `StandardScaler`

## 2. Exploratory Data Analysis (EDA)
Performed visual and statistical analysis to understand customer behavior:
- Age distribution analysis
- Income distribution analysis
- Spending score analysis
- Gender distribution
- Scatter plot between Annual Income and Spending Score

## 3. K-Means Clustering
- Applied the Elbow Method to determine the optimal number of clusters
- Trained the K-Means clustering model
- Assigned cluster labels to customers

## 4. Cluster Visualization
Used dimensionality reduction techniques:
- PCA (Principal Component Analysis)
- t-SNE visualization

These techniques helped visualize customer segments in 2D space.

## 5. Marketing Strategy Development
Created marketing recommendations for each customer segment based on spending and income behavior.

---

# Results and Findings

## Key Findings
- Customers were successfully divided into multiple meaningful groups.
- High-income customers do not always have high spending behavior.
- Some customer groups showed strong purchasing potential.
- K-Means clustering effectively identified customer patterns.

## Identified Customer Segments
1. High Income – High Spending
2. High Income – Low Spending
3. Low Income – High Spending
4. Low Income – Low Spending
5. Average Customers

## Business Insights
- Premium customers can be targeted with VIP memberships and luxury products.
- Low-spending high-income customers may respond well to personalized marketing.
- Discount campaigns work effectively for budget-conscious customers.
- Customer segmentation helps improve marketing efficiency and customer engagement.

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

# Machine Learning Techniques

- K-Means Clustering
- PCA (Principal Component Analysis)
- t-SNE

---

# Project Outcome

This project demonstrates how unsupervised machine learning can help businesses better understand customer behavior and make data-driven marketing decisions through customer segmentation.
