Analysis of forest fires using probability and statistics

 Forest Fires Analysis 

Statistical analysis of forest fire data to identify key factors 
that influence the burned area.

 About
This project applies probability and statistics methods to analyze 
a forest fires dataset, examining the relationship between weather 
conditions and the size of burned areas.

 Dataset
- Source: forestfires_filledgt.csv
- Variables: temperature, humidity, wind speed, rainfall, burned area

 Methods and Techniques

  Regression Analysis
- Simple Linear Regression - temperature vs burned area
- Multiple Linear Regression - temperature, rainfall and wind speed vs burned area
- Quadratic Regression - non-linear relationship testing
- Cubic (Polynomial) Regression - higher-order relationship testing

  Probability
- Unconditional probability - P(temperature > 25), P(burned area > 100)
- Conditional probability - P(burned area > 100 | temperature > 25)

  Statistics
- Parameter estimation - mean, variance, standard deviation, min, max, median, quartiles
- Covariance and correlation - relationship between temperature and burned area
- Confidence interval - 95% confidence interval for mean temperature

 Technologies
- Python, Pandas, NumPy
- Statsmodels (OLS regression)
- Scipy (statistics, confidence intervals)
- Matplotlib (visualization)

 Key Findings
- Temperature has a weak positive effect on burned area (r ≈ 0.17)
- Rainfall has a strong negative effect on burned area
- Wind speed does not show statistically significant influence
- Multiple regression outperforms simple linear regression
- Temperature alone is not sufficient to predict burned area accurately
