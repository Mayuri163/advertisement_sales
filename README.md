# advertisement_sales
## Project Overview
This project analyzes how advertisement spending on TV, Radio, and Newspaper influences product Sales. Using a linear regression model, we identified which channels contribute the most to driving sales.

**Dataset**
The dataset contains 200 observations with the following columns:

1.TV: Advertisement cost for TV (in thousands of dollars)
2.Radio: Advertisement cost for Radio
3.Newspaper: Advertisement cost for Newspapers
4.Sales: Product sales (in thousands of units)

**Methodology**
1. Correlation Analysis
We performed a correlation analysis to understand the relationship between advertisement spending and sales. TV and radio ads showed a strong correlation with sales, while newspaper ads had a weaker correlation.

2. Linear Regression Model
A multiple linear regression model was built using TV, Radio, and Newspaper as independent variables, and Sales as the dependent variable.

**Key metrics from the model:**

R-squared: 0.897 (The model explains 89.7% of the variance in sales)
Adjusted R-squared: 0.896
F-statistic: 859.6 (p-value: 4.83e-98)
Model coefficients:

Intercept: 2.9211
TV: 0.0458 (p < 0.001)
Radio: 0.1880 (p < 0.001)
Newspaper: Insignificant in contributing to sales.

**Results**
The regression analysis showed that TV and Radio advertisements have the most significant impact on sales. Newspaper ads have a minimal effect on sales.

**Conclusion**
By analyzing the dataset, we found that investing in TV and radio ads is more effective in driving product sales compared to newspaper advertisements.
