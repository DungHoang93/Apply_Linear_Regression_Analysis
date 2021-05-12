LINEAR REGRESSION

 This note aims to understand the basis of linear regression through:

    Fit a simple OLS linear regression model
    Use both quantitative and binary categorical predictors
    Interpret the coefficients of a regression model
    Check the assumptions of a regression model
    
Dataset and the main structure of this project are from the course Introduction to Linear Regression - Codecademy

The new dataset named website contains simulated data for a sample of visitors to a website, including the amount of time in seconds they spent on the website (time_seconds), their age (age), and information about whether they accessed the website using Chrome or Safari (browser). The Notebook is used to answer the questions below:

- Quantitative predictors
 1. Create a plot of time_seconds (vertical axis) versus age (horizontal axis). Is there a linear relationship between these variables?
 2. Fit a linear model to predict time_seconds using the age variable
 3. Use the coefficients from the linear model to plot the regression line on top of your original plot.
 4. Calculate the fitted values and residuals
 5. The normality assumption by plotting a histogram of the residuals. Are they approximately normally distributed?
 6. The homoscedasticity assumption by plotting a the residuals against the fitted values. Is this assumption satisfied?
 7. Use your model to predict the amount of time that a 40 year old person will spend on the website.

- Binary categorical predictors
1. Fit another model that predicts time_seconds based on web_browser.
2. Print out the coefficients. What is the difference in average time spent on each browser?
