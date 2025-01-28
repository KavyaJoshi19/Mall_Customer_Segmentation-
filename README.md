

# Mall Customer Segmentation

## Overview  
This project focuses on segmenting customers of a mall into distinct groups based on their purchasing behavior and demographics. The goal is to help the business understand customer patterns and design targeted marketing strategies.

## Dataset  
The dataset includes customer attributes:  
- **CustomerID**: Unique identifier  
- **Gender**: Male/Female  
- **Age**: Customer's age  
- **Annual Income (k$)**: Income in thousands of dollars  
- **Spending Score (1-100)**: Score assigned based on spending behavior  

## Approach  
1. **Data Preprocessing**  
   - Checked for missing values and outliers.  
   - Scaled numerical features for consistency.  

2. **Clustering**  
   - Explored **K-Means Clustering** for segmentation.  
   - Used **Elbow Method** to determine the optimal number of clusters.  
   - Visualized clusters using a 2D plot for better interpretation.

3. **Insights**  
   - Identified customer segments based on income and spending behavior:  
     - High income, high spenders  
     - Low income, low spenders  
     - Moderate income, selective spenders, etc.  

## Tools & Libraries  
- **Python**  
- **NumPy, Pandas** for data manipulation  
- **Matplotlib, Seaborn** for visualization  
- **Scikit-learn** for clustering  

## Key Results  
- Successfully segmented customers into meaningful groups.  
- Provided actionable insights for personalized marketing and resource allocation.  

## Usage  
Run the notebook `mall_customer_segmentation.ipynb` to reproduce results and experiment with clustering techniques.

