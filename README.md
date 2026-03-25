# Housing Price Analysis (1.35M+ Listings)

This project analyzes a large-scale U.S. housing dataset with over 1.3 million observations to understand the relative importance of property features and location characteristics in determining housing prices.

## Research Question

What is the relative importance of physical property features versus location characteristics in determining housing prices, and how does their influence vary across different price segments?

## Dataset

- Source: USA Real Estate Dataset (Kaggle / Realtor.com)
- Observations: 1,350,000+
- Response Variable: Housing price (log-transformed)

## Methodology

- Data cleaning and preprocessing  
- Log transformation to address skewness  
- Multiple linear regression  
- Model comparison (3 models):
  - Model 1: Demographic & economic variables  
  - Model 2: Property features  
  - Model 3: Combined model  
- Model diagnostics:
  - Residual plots  
  - Q-Q plots  
  - Heteroscedasticity checks  

## Key Results

- Combined model achieved the best performance (R² ≈ 0.44)  
- Property features (bathrooms, house size) showed strong positive effects  
- Location-related variables (GDP, demographics) significantly influenced prices  
- Different factors dominate across different segments of the housing market  

## Key Insights

- Housing prices are driven by both micro-level (property) and macro-level (location) factors  
- Physical features matter consistently across price levels  
- Economic and demographic context plays a stronger role in higher-value markets  

## Files

- `STA302 Final Project.pdf`: Full report  
- `housing-price-analysis.Rmd`: Analysis code  
- `/images`: Selected visualizations

- https://github.com/lilshulin/data-analysis-portfolio/blob/2a211a0fd213c26f926d433d242c2c570f3c8f4a/histogram.png

## Author

Shulin Li  
