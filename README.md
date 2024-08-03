# Customer Personality Analysis

## Overview

This project aims to analyze customer data from a marketing campaign to identify different customer segments and understand their characteristics. The analysis includes data cleaning, exploratory data analysis (EDA), and clustering techniques to categorize customers based on their behaviors and demographics.

## Data Description

The dataset used in this analysis is named `marketing_campaign.csv`. It contains various features related to customer demographics, purchase history, and responses to marketing campaigns.

### Key Features
- **Demographic Information**: Age, income, education level, marital status, etc.
- **Purchase History**: Amount spent on different product categories, number of purchases, etc.
- **Response to Campaigns**: Number of complaints, response to different marketing campaigns, etc.

## Steps and Methodology

1. **Data Import and Libraries**: 
   - The analysis uses libraries such as Pandas, Seaborn, Plotly, and Matplotlib for data manipulation and visualization.

2. **Data Loading**: 
   - The dataset is loaded using Pandas, and an initial copy is made to preserve the original data.

3. **Exploratory Data Analysis (EDA)**:
    - **Data Shape and Info**: The dataset's shape and basic information are checked to understand its structure.
    - **Unique Values**: The number of unique values in each column is identified to detect any columns with constant values.
    - **Missing Values**: Missing values are identified, especially in the 'Income' column. A heatmap visualization helps in understanding the distribution of missing data.
    - **Data Cleaning**: Columns with constant values, such as "Z_CostContact" and "Z_Revenue", are dropped as they do not contribute to the analysis.

4. **Customer Complaints and Responses**:
    - The number of complaints and customer responses to campaigns over the last two years are analyzed.

5. **Customer Segmentation**:
    - Customers are segmented into different clusters using clustering techniques. The analysis identifies three main clusters:
        1. **Highly Active Customers**
        2. **Moderately Active Customers**
        3. **Least Active Customers**

6. **Cluster Characteristics**:
    - **Highly Active Customers**: Predominantly with PG backgrounds, mostly in relationships, with moderate income, having more children, and showing high loyalty.
    - **Moderately Active Customers**: Also with PG backgrounds, slightly higher income, fewer children, and significant spending.
    - **Least Active Customers**: Characterized by lower engagement and different demographic profiles compared to the other clusters.

## Conclusion

The analysis provides insights into customer segments, helping in understanding customer behavior, preferences, and loyalty. These insights can guide targeted marketing strategies and improve customer engagement.

## Requirements

The analysis requires the following Python libraries:
- pandas
- seaborn
- plotly
- matplotlib

## How to Run

To run this analysis, ensure you have the necessary libraries installed. Load the notebook in a Jupyter environment and execute the cells sequentially.
