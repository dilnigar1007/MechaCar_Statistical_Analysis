# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Based on the results we can conclude that both ground_clearance and vehicle_length provided a non-random amount of variance to the mpg values since they both have extremely small p-value or in another word, significant to the model.
[!summary](https://github.com/dilnigar1007/MechaCar_Statistical_Analysis/blob/main/images/summary.png)

2. Is the slope of the linear model considered to be zero? Why or why not?
According to the results summary, some of these six variables had significant effect on the mpg, therefore slope can’t be zero. 

3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Our r-squared is 0.7149 in this model, that means 71% of the variability observed in the target variable is explained by the regression model, so we can say this linear model predicts mpg of MechaCar prototypes effectively. 

## Summary Statistics on Suspension Coils
If we look at the total_summary variance, it meets the requirement since the variance is 62.29. But if we look at each individual lot, then lot 1 and lot 2 meet the requirement, lot 3 fails to meet the requirement since the variance for lot 3 is 170.29.

## T-Tests on Suspension Coils
[!t-test](https://github.com/dilnigar1007/MechaCar_Statistical_Analysis/blob/main/images/t-test.png)
P-value for the three lots combined, we have 0.06028 which is higher than our critical value of 0.05, so we fail to reject the null hypothesis that there is a statistical difference between the different lots and the population mean of 1,500.
[!t-test-lot1](https://github.com/dilnigar1007/MechaCar_Statistical_Analysis/blob/main/images/t-test(lot1).png)
[!t-test-lot2](https://github.com/dilnigar1007/MechaCar_Statistical_Analysis/blob/main/images/t-test(lot2).png)
[!t-test-lot3](https://github.com/dilnigar1007/MechaCar_Statistical_Analysis/blob/main/images/t-test(lot3).png)

##Study Design: MechaCar vs Competition
