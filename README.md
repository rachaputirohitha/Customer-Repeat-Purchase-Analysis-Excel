# Customer Repeat Purchase Analysis – Excel

## Task Overview

This project focuses on analyzing customer repeat purchase behavior using Microsoft Excel.

The analysis identifies first-time and repeat customers and calculates the overall repeat purchase rate.

## Dataset

**Dataset:** Online Retail II

The dataset contains retail transaction information such as:

- Invoice
- Stock Code
- Description
- Quantity
- Invoice Date
- Price
- Customer ID
- Country

A Sales column was also created for the analysis.

## Tools Used

- Microsoft Excel
- Pivot Tables
- Excel Formulas
- Data Cleaning
- Data Visualization

## Analysis Performed

### 1. Sales Calculation

Created a Sales column using:

`Sales = Quantity × Price`

### 2. Customer Order Analysis

Created a Customer Orders table using:

- Invoice
- Customer ID

Duplicate Invoice–Customer ID combinations were removed to identify unique customer orders.

### 3. Customer Segmentation

Customers were classified into two groups:

- First-time Customers
- Repeat Customers

The segmentation was based on the number of unique invoices associated with each customer.

### 4. Repeat Purchase Rate

The repeat purchase rate was calculated as:

`Repeat Purchase Rate = Repeat Customers / Total Customers × 100`

### Results

| Customer Segment | Number of Customers |
|------------------|---------------------|
| First-time       | 1,313               |
| Repeat           | 3,061               |
| Total            | 4,374               |

**Repeat Purchase Rate: 69.98% (approximately 70%)**

## Visualization

A pie chart was created to visualize the distribution of:

- First-time Customers
- Repeat Customers

## Key Findings

- There were **4,374 customers** analyzed.
- **3,061 customers** were identified as repeat customers.
- **1,313 customers** were identified as first-time customers.
- The repeat purchase rate was approximately **70%**.
- Repeat customers represent the larger share of the customer base.

## Skills Practiced

- Excel data cleaning
- Pivot Tables
- Duplicate removal
- Customer segmentation
- IF formula
- Percentage calculation
- Data visualization
- Business insights

## Conclusion

The analysis shows that approximately **70% of the analyzed customers were repeat customers**, indicating a strong level of repeat purchasing behavior in the dataset.

## Screenshots
<img width="1600" height="900" alt="Screenshot (539)" src="https://github.com/user-attachments/assets/55ee7135-2c31-4518-b3d1-70e6e8c138b5" />

<img width="1600" height="900" alt="Screenshot (540)" src="https://github.com/user-attachments/assets/498171df-38f1-498f-a048-9787148f8102" />

<img width="1600" height="900" alt="Screenshot (541)" src="https://github.com/user-attachments/assets/48d6799e-c9d4-4a40-acfa-b3149253c32e" />



