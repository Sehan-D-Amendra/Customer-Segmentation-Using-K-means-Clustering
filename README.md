# Customer Segmentation Using K-means Clustering

### Project Overview
This project implements customer segmentation using K-means clustering on retail purchase history data. By analyzing customer behavior patterns, the system identifies distinct customer segments that can be targeted with personalized marketing strategies.

### Dataset
The analysis uses the "Online Retail" dataset, which contains transactions from a UK-based online retail store. The dataset includes:

- Customer IDs
- Transaction details
- Product information
- Purchase timestamps
- Pricing data

### Objectives
- Segment customers based on their purchasing behavior
- Identify valuable customer groups
- Develop targeted marketing strategies
- Visualize customer segments for business insights
- Provide actionable recommendations for each segment

## Technologies Used
- Python 3.x
- pandas, numpy for data manipulation
- scikit-learn for machine learning algorithms
- matplotlib, seaborn for data visualization
- Jupyter Notebook for development and documentation

## Results
- The analysis identifies distinct customer segments such as:
- Champions (high-value, frequent shoppers)
- Loyal Customers (consistent shoppers)
- New Customers (recent first-time buyers)
- At-Risk Customers (decreasing engagement)
- Dormant Customers (inactive accounts)

Each segment is profiled with characteristics including average purchase recency, frequency, and monetary value, allowing for tailored marketing approaches.

## Files in the Repository
- customer_segmentation.py: Main Python script
- customer_segmentation.ipynb: Jupyter notebook with step-by-step analysis
- customer_segments.csv: Output file with customer segment assignments
- marketing_strategies.csv: Generated marketing recommendations
