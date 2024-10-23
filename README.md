# TV_Sales_Prediction_Linear_Regression
A linear regression analysis on marketing sales data, exploring the impact of TV promotional budgets on sales. Implemented Ordinary Least Squares (OLS) and checked model assumptions, including linearity, normality, independent observations, and homoscedasticity. Visualizations are included to support insights and findings.

**Project Findings:**

**Model Summary:** Simple Linear Regression on marketing sales data.

**Y-intercept:** -0.1263, Slope: 3.5614.

**Interpretation:** A $1 million increase in TV promotional budget leads to an average sales increase of $3.5614 million.

**Statistical Significance:** p-value = 0.000 (significant at 0.05 level).

**Hypothesis Testing:** Reject the null hypothesis (no relationship between TV budget and sales).

**Confidence Interval:** 95% CI for the slope: [3.558, 3.565], meaning the true slope likely falls in this range.

**Table of Contents:**

Project Overview
Data Exploration
Model Building
Results
Assumption Checks
Conclusion
Technologies Used

**1. Project Overview:**

The goal of this analysis is to examine the impact of TV promotional budgets on sales using ordinary least squares (OLS) linear regression. The analysis provides insights into how much TV promotion affects sales performance.

**2. Dataset:**

The dataset used in this analysis is named marketing_sales_data.csv, which includes the following columns:

TV: Category of TV advertising spend (Low, Medium, High)

Radio: Amount spent on radio advertising (in millions)

Social Media: Amount spent on social media advertising (in millions)

Influencer: Type of influencer marketing (Micro, Macro, Mega, Nano)

Sales: Total sales generated (in millions)

**3. Data Exploration:**

The initial exploration of the dataset includes:

Displaying the first 10 rows of data.

Checking for null values.

Dropping rows with null values.

A pairwise relationship plot was created to visualize the correlations among the variables.

**4. Model Building:**

The following steps were taken to build the linear regression model:

OLS Data Preparation: Selected TV and Sales columns for the analysis.

Linear Regression Formula: Defined the formula as Sales ~ TV.

Model Fitting: Implemented the OLS approach and fit the model to the data.

**5. Results:**

The regression model summary provides key insights:

Model Equation: [ y{Sales} = 3.5614 * x{TV} - 0.1263 ]

Y-intercept: -0.1263

Slope: 3.5614 (indicates sales increase by $3.5614 million for every $1 million increase in TV budget)

R-squared: 0.999 (99.9% of sales variability explained by TV budget)

p-value: 0.000 (statistically significant relationship)

**6. Assumption Checks:**

To ensure the validity of the linear regression model, the following assumptions were checked:

Linearity: Confirmed through scatterplots and regression plots.

Normality of Residuals: Visualized using histograms and Q-Q plots.

Independence of Observations: Residuals vs. fitted values showed no patterns.

Homoscedasticity: Residuals appeared randomly spaced.

**7. Conclusion:**

The analysis demonstrates a significant positive relationship between TV promotional budgets and sales. The results suggest that increasing the TV budget leads to higher sales, providing a data-driven foundation for marketing decisions.

**8. Technologies Used:**

Python

Pandas

NumPy

Matplotlib

Seaborn

Statsmodels

