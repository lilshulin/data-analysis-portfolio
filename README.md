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
- `/images`: 
- https://github.com/lilshulin/data-analysis-portfolio/blob/2a211a0fd213c26f926d433d242c2c570f3c8f4a/histogram.png
- https://github.com/lilshulin/data-analysis-portfolio/blob/b2f46b37cf165d2de5ac7c25728aa7c25ad9e29b/price%20and%20house%20size.png
- https://github.com/lilshulin/data-analysis-portfolio/blob/c6b0eb2415a4412c99d0126b4fcf0c5a77920a34/QQ.png
- https://github.com/lilshulin/data-analysis-portfolio/blob/98bf1e1e9e31c0b4b7f3c465529e082947195d49/residual%20and%20fitted.png

## Author

Shulin Li  
