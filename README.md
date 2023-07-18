# RFM Segmentation for Targeting CRM
## Objective
The goal of this project is to use RFM analysis to segment customers based on their purchase data. By using this analysis, we can distinguish between loyal customers, potential loyal customers, churned customers, and customers at risk of churning, etc. This information can be used to conduct more precise customer relationship management (CRM) and improve customer satisfaction.

## Data Description
I have utilized publicly available sales data, which has been anonymized and processed for the purpose of analysis.
The dataset contains transaction data, where each row represents an individual order and the columns include information such as Order Date, Customer ID, Product Number, Price, Sector, Category, and Subcategory.

## Method
The code follows several steps to achieve this goal:

Recency Calculation: Calculate the Recency value for each customer by finding the number of days since their last purchase.

Frequency Calculation: Calculate the Frequency value for each customer by counting the number of orders they have made.

Monetary Calculation: Calculate the Monetary value for each customer by summing the total amount they have spent.

RFM Score Calculation: Calculate the R, F, and M scores for each customer by dividing them into quintiles based on their Recency, Frequency, and Monetary values. Sum these scores to get a total RFM score for each customer.

Visualization: Create a confusion matrix to visualize the distribution of customers across different RFM segments.

## Results

The resulting RFM scores represent different segments of customers based on their purchasing behavior. By understanding these segments, we can tailor our marketing and sales strategies to better meet the needs of different groups of customers.

![image](https://github.com/githubinsu/RFM-Segmentation/assets/130045953/17e8d3cf-45d4-483e-b88d-79b95a5221e8)
