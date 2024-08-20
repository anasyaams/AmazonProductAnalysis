# Amazon Product Analysis

The dataset contains various information about products sold on Amazon, including: prices, ratings, availability, sales volume, and product category(best seller, amazon choice, prime, climate_pledge_friendly). 
1. Preprocessing
   - Handle missing values with mean for numerical columns and mode for categorical columns
   - Convert product price and sales volume to float
3. Descriptive statistics
   - Calculate summary statistics for numeric columns (average, median, min, max)
   - Frequency counts for categorical columns (how many products are best sellers, Amazon's Choice, Prime eligible)
5. Price analysis
   - Compare the current price to the original price to assess discount levels
7. Rating analysis
   - Examine the distribution of product ratings
   - Correlate the number of ratings with the average star rating to identify trends
9. Sales Volume Analysis
    - Identify top-selling products
    - Analyze sales volume in relation to pricing, rating, and other attributes
11. Product Categorization
    - Perform KNN clustering to identify patterns or segments among products
11. Predictive Modeling
    - Create heatmaps to show correlations between different features
    - Use Ridge Regression models to predict product prices based on features
    - Predict product ratings using Linear Regression based on features
13. Classification Tasks
    - Classify products into different categories (e.g., best seller, Amazon's Choice) using Random Forest classification
