# Customer Segmentation Analysis

## Project Overview

This project performs customer segmentation using RFM analysis and K-Means clustering on the Online Retail dataset.

The objective is to identify different customer groups based on purchasing behavior and provide business recommendations for targeted marketing strategies.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Power BI

## Analysis Performed

### Data Cleaning
- Removed duplicate records
- Removed missing Customer IDs
- Removed cancelled transactions
- Removed invalid quantities
- Removed invalid unit prices
- Created Revenue column

### RFM Analysis

RFM stands for:

- Recency
- Frequency
- Monetary

Customers were scored based on their purchasing behavior.

### K-Means Clustering

K-Means clustering was applied using:

- Recency
- Frequency
- Monetary

The Elbow Method and Silhouette Score were used to evaluate the appropriate number of clusters.

## Customer Segments

The final customer groups were:

### Champions
Recent, highly frequent and high-value customers.

### Potential Loyalists
Recently active customers with potential to become loyal customers.

### At Risk
Previously valuable customers who have not purchased recently.

### Lost Customers
Low-engagement customers with long periods since their last purchase.

## Business Recommendations

- Champions: Focus on retention, VIP rewards and exclusive offers.
- Potential Loyalists: Encourage repeat purchases and loyalty enrollment.
- At Risk: Use personalized win-back campaigns.
- Lost Customers: Use selective reactivation campaigns.

## Dashboard

An interactive Power BI dashboard was created to visualize:

- Customer KPIs
- Customer segment distribution
- Revenue by segment
- RFM analysis
- K-Means clusters
- Customer performance
- Country-level analysis

## Project Structure

# Customer Segmentation Analysis

## Project Overview

This project performs customer segmentation using RFM analysis and K-Means clustering on the Online Retail dataset.

The objective is to identify different customer groups based on purchasing behavior and provide business recommendations for targeted marketing strategies.

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook
- Power BI

## Analysis Performed

### Data Cleaning
- Removed duplicate records
- Removed missing Customer IDs
- Removed cancelled transactions
- Removed invalid quantities
- Removed invalid unit prices
- Created Revenue column

### RFM Analysis

RFM stands for:

- Recency
- Frequency
- Monetary

Customers were scored based on their purchasing behavior.

### K-Means Clustering

K-Means clustering was applied using:

- Recency
- Frequency
- Monetary

The Elbow Method and Silhouette Score were used to evaluate the appropriate number of clusters.

## Customer Segments

The final customer groups were:

### Champions
Recent, highly frequent and high-value customers.

### Potential Loyalists
Recently active customers with potential to become loyal customers.

### At Risk
Previously valuable customers who have not purchased recently.

### Lost Customers
Low-engagement customers with long periods since their last purchase.

## Business Recommendations

- Champions: Focus on retention, VIP rewards and exclusive offers.
- Potential Loyalists: Encourage repeat purchases and loyalty enrollment.
- At Risk: Use personalized win-back campaigns.
- Lost Customers: Use selective reactivation campaigns.

## Dashboard

An interactive Power BI dashboard was created to visualize:

- Customer KPIs
- Customer segment distribution
- Revenue by segment
- RFM analysis
- K-Means clusters
- Customer performance
- Country-level analysis

## Project Structure

CustomerSegmentation/

├── data/

├── notebooks/

├── powerbi/

├── images/

├── README.md

└── requirements.txt