# Customer Segmentation Using RFM and K-Means

## Overview
This project segments customers based on purchasing behavior using RFM analysis and K-means clustering to support targeted marketing strategies.

## Dataset
Based on the UCI Online Retail dataset.  
Due to file size limitations, the full raw data is not included.  
The repository provides the processed `rfm_table.csv` used for clustering.

## Methodology
- Data cleaning and preprocessing  
- RFM feature construction (Recency, Frequency, Monetary)  
- Log transformation and robust scaling  
- K-means clustering and model selection (Elbow + Silhouette)

## Results
A 4-cluster solution identifies:
- Loyal high-value customers  
- Inactive customers  
- Recent low-value customers  
- Regular mid-value customers  

## Business Impact
The segmentation supports:
- retention and loyalty strategies  
- reactivation campaigns  
- customer growth and upselling  

## Structure
- `notebooks/` → full analysis  
- `data/` → processed RFM dataset  
