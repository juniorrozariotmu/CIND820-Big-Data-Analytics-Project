# CIND820 - Big Data Analytics Project  
## Data Mining for Customer Behaviour Analysis in Retail Sales *(WIP)*

---

## Project Overview

This project applies data mining techniques to retail transactional data to uncover patterns in customer purchasing behavior.  

The analysis integrates:
- Customer segmentation (clustering)
- Market basket analysis (association rule mining)
- Revenue driver analysis (regression)

The goal is to generate actionable insights that support:
- Cross-selling strategies  
- Customer targeting  
- Revenue optimization  

---

## Research Questions

1. **Customer Segmentation**  
   What distinct retail customer segments can be identified using behavioral clustering techniques based on recency, frequency, monetary value, and basket characteristics?

2. **Association Rule Mining**  
   How do product association patterns differ across identified customer segments, and which segment-specific product combinations demonstrate the strongest cross-selling potential based on support, confidence, and lift?

3. **Revenue Driver Analysis**  
   How do the individual behavioral components of RFM (Recency, Frequency, and Average Basket Size) structurally relate to overall retail revenue (Monetary), and what do these relationships suggest for marketing prioritization and resource allocation?

---

## Dataset

- **Name:** Online Retail Dataset  
- **Source:** UCI Machine Learning Repository  
- **Time Period:** January 2010 – September 2011  

### Key Fields
- Invoice Number  
- Stock Code  
- Product Description  
- Quantity  
- Invoice Date  
- Unit Price  
- Customer ID  
- Country  

This dataset contains transactional records from a UK-based online retail company that primarily sells unique, all-occasion gift items.

---

## Methodology

The project follows a structured data mining workflow:

### 1. Exploratory Data Analysis (EDA)
- Summary of dataset structure (shape, missing values, data types)
- Dataset variable overview 
- Data quality checks (missing Customer IDs, cancellations, outliers)
- Temporal analysis of sales trends over time

---

### 2. Data Cleaning & Preparation
- Handling missing Customer IDs  
- Removing cancellations and invalid transactions  
- Feature engineering (RFM + basket metrics)

---

### 3. Customer Segmentation
- K-Means clustering  
- Hierarchical clustering (validation & comparison)

---

### 4. Market Basket Analysis
- Association rule mining using support, confidence, and lift  
- Segment-level pattern comparison  

---

### 5. Revenue Analysis
- Regression modeling to analyze structural relationships between behavioral features and revenue  

---

## Repository Contents

- `*.ipynb` → Jupyter Notebook containing full analysis  
- `*.html` → Exported version of the notebook for easier viewing  

---

## Reproducibility

To reproduce this project:

1. Clone the repository

2. Install required dependencies

3. Download the dataset from the UCI Machine Learning Repository and place it in the project directory

4. Run the Jupyter Notebook
