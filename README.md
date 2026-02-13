Customer Segmentation using RFM Analysis
 # Project Overview
This project performs Customer Segmentation using the RFM (Recency, Frequency, Monetary) model on the Online Retail dataset. The goal is to identify high-value and at-risk customers to support targeted marketing and retention strategies.

# Dataset
Dataset: Online Retail Dataset

Format: CSV

Key Columns: InvoiceNo, InvoiceDate, CustomerID, Quantity, UnitPrice

# Data Preprocessing
Removed null CustomerID values

Removed cancelled invoices

Filtered negative quantities

Converted InvoiceDate to datetime format

Created TotalPrice column (Quantity × UnitPrice)

# RFM Calculation
Recency: Days since last purchase

Frequency: Number of unique transactions

Monetary: Total amount spent

Customers were scored using quantile-based ranking (1–4 scale).

# Customer Segments
Champions

Loyal Customers

Potential Loyalists

At Risk

Hibernating

Lost

# Visualization
Bar chart showing customer segment distribution

# Output
Exported final RFM segmentation table as CSV

# Technologies Used
Python

Pandas

NumPy

Matplotlib

