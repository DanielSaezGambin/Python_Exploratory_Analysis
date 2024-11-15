# Python_Exploratory_Analysis
# Exploratory Analysis of Men's Fashion Products on Shein

This project performs an exploratory data analysis (EDA) of men's fashion products available on Shein, focusing on identifying key patterns, distributions, and correlations within the dataset.

## Objective
To analyze product trends, review distributions, and the relationship between discounts and reviews, providing insights for improving marketing strategies and product optimization.

## Dataset
- **Size**: 1000 products  
- **Features**:  
  - `color`  
  - `category_name`  
  - `reviews_count`  
  - `average_rating`  
  - `discount_percentage`

## Methodology
1. **Data Preparation**  
   - Check and handle missing values.  
   - Standardize `color` and `category_name`.

2. **Exploratory Analysis**  
   - **Variable Distribution**:  
     - Use histograms to explore the frequency of `reviews_count` and `average_rating`.  
   - **Top Products**:  
     - Focus on products with over 1000 reviews.  
     - Visualize dominant categories using bar charts.

3. **Color and Category Analysis**  
   - Group products by `color` and `category_name`.  
   - Analyze median reviews by group and create bar plots to compare variations.

4. **Correlation Analysis**  
   - Calculate correlations between `discount_percentage` and `reviews_count` across categories and colors.

## Insights
- Popular categories and colors among top-reviewed products.  
- Distribution of reviews and ratings.  
- The impact of discounts on review counts.

## Applications
- Supports purchase decision-making.  
- Enhances product and marketing strategy optimization on Shein.

This analysis offers actionable insights for data-driven decision-making in the e-commerce space. 🚀
