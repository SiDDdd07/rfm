# Customer Segmentation & Retention Analytics

## Problem Statement

Businesses often treat all customers the same, despite differences in purchasing behavior and value. Without understanding which customers are loyal, at risk, or high value, companies struggle to design effective retention and marketing strategies.

This project aims to analyze customer purchasing patterns and segment customers into meaningful groups to support data-driven retention decisions.

---

## Objective

The objectives of this project are to:

- Understand customer purchasing behavior.
- Segment customers based on Recency, Frequency, and Monetary (RFM) metrics.
- Identify high-value, loyal, and at-risk customers.
- Discover natural customer groups using clustering.
- Recommend targeted retention and engagement strategies.
- Predict future customer behavior using machine learning.

---

## Dataset

The dataset contains transaction-level information, including:

- Customer ID
- Invoice Number
- Invoice Date
- Product Description
- Quantity
- Unit Price
- Country

The data was cleaned by:

- Removing cancelled transactions.
- Removing missing customer IDs.
- Filtering invalid quantities.
- Creating total revenue features.

---

## Methodology

### 1. Data Cleaning and Preprocessing

- Removed missing values and cancelled orders.
- Created transaction revenue features.
- Converted dates into appropriate formats.

---

### 2. RFM Analysis

Customers were evaluated using:

- **Recency** – How recently a customer purchased.
- **Frequency** – How often a customer purchases.
- **Monetary Value** – How much a customer spends.

Based on these metrics, customers were grouped into segments such as:

- Champions
- Loyal Customers
- Potential Loyalists
- At-Risk Customers
- Lost Customers

---

### 3. Customer Segmentation using K-Means Clustering

K-Means clustering was applied to identify natural groups of customers.

The Elbow Method was used to determine the optimal number of clusters.

Cluster characteristics were analyzed based on:

- Average Recency
- Average Frequency
- Average Monetary Value

---

### 4. Exploratory Data Analysis

Performed analysis to understand:

- Distribution of RFM metrics.
- Segment-wise customer composition.
- Revenue contribution by customer groups.
- Product purchasing trends.
- Country-level customer distribution.

Visualizations included:

- Histograms
- Cluster analysis plots
- Treemaps
- Segment comparisons

---

### 5. Customer Behavior Modeling

Built a machine learning model using:

- Random Forest Regressor

Features used:

- Recency
- Frequency
- Monetary Value
- Average Inter-Purchase Time

The model was used to understand future customer purchasing patterns and estimate customer activity.

---

## Key Insights

### Champions

- Highly valuable customers.
- Frequent purchasers with strong engagement.
- Major contributors to revenue.

### Loyal Customers

- Consistent buyers with high retention potential.
- Ideal targets for loyalty programs.

### Potential Loyalists

- Customers showing promising behavior.
- Can be nurtured into high-value customers.

### At-Risk Customers

- Previously active customers with declining engagement.
- Require re-engagement campaigns.

### Lost Customers

- Long periods without purchases.
- Low probability of returning without incentives.

---

## Business Recommendations

### For Champions

- Offer loyalty rewards.
- Provide early access to products.
- Create premium experiences.

### For Loyal Customers

- Encourage repeat purchases through personalized offers.
- Cross-sell complementary products.

### For Potential Loyalists

- Send targeted recommendations.
- Introduce membership benefits.

### For At-Risk Customers

- Run win-back campaigns.
- Offer personalized discounts.

### For Lost Customers

- Use low-cost email campaigns and promotions.

---

## Tech Stack

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Scikit-Learn

---

## Machine Learning Techniques Used

- RFM Analysis
- Feature Engineering
- Standard Scaling
- K-Means Clustering
- Elbow Method
- Random Forest Regression

---

## Business Impact

This framework helps businesses:

- Identify high-value customers.
- Improve retention strategies.
- Optimize marketing efforts.
- Increase customer lifetime value.
- Understand purchasing behavior.
- Enable data-driven decision making.

---

## Conclusion

Customer segmentation provides a deeper understanding of customer behavior and enables businesses to move from one-size-fits-all marketing to targeted retention strategies. By combining RFM analysis, clustering, and predictive modeling, this project demonstrates how analytics can help improve customer engagement and long-term business growth.


