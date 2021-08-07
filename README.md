# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
- According to our results of statistical summary of multiple linear regression, we can assume that vehicle length, ground clearance and intercept provide a non-random amount of variance to the mpg values and have significant impact on the mpg, because their Pr(>|t|) values are close to zero. 
- Slope or p-value of the multiple linear model is 5.35e-11, which is not equal to zero. Therefore we can reject null hypothesis and consider that there is a relationship between independent and dependent values.
- Also adjusted R-squared value is 0.68, which indicates on high correlation level and the model can be considered capable to predict mpg of MechaCar prototypes effectively.

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 PSI. According to overall analysis of Suspension Coil data, variance is 62.29, which is below the threshold. But after grouping the results by lots we can see the big difference between lots. Lots 1 and 2 have good results (0.98 and 7.47 relatively) and lot 3 is way above the limit (170.29). Here we assume that grouping helps to reveal weaknesses in production.
