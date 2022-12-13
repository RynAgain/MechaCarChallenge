# MechaCarChallenge
## Deliverable 1: Predict MPG using Linear Regression
![D1_linear_regression.png](/Resources/Photos/D1_linear_regression.png)

Q: Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
A: The variance of vehicle length and ground clearance are not random and have a low p-value when applied to the mpg.

Q: Is the slope of the linear model considered to be zero? Why or why not?
A: The slope is not zero and is significantly smaller than 0.05, thus the null hypothesis is rejected.

Q:  Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
A: The linear regression model is effective because it explains about 70% of the variance in the MPG. This is indicated by the R-squared value, which measures the proportion of the variance in the dependent variable (MPG in this case) that is explained by the model. A value of 0.7 suggests that the model is able to accurately predict the MPG for a given set of independent variables (such as vehicle length and ground clearance) with good accuracy.


## Deliverable 2: Suspension Coils Summary

## Summary Statistics on Suspension Coils
![D2_lot_summary.png](/Resources/Photos/D2_lot_summary.png)


![D2_total_summary.png](/Resources/Photos/D2_total_summary.png)

Q: There is a summary that addresses the design specification requirement for all the manufacturing lots and each lot individually
A: The hypothesis is supported by the data from Lot1 and Lot2, but the data from Lot3 shows too much variance in the PSI measurements to support the hypothesis. This suggests that the hypothesis may not hold for all lots, and further investigation may be needed to understand the reasons for the variance in the PSI measurements in Lot3.



## Deliverable 3: T-Tests on Suspension Coils

- There is a summary of the t-test results across all manufacturing lots and for each lot.

![ttest_all.png](/Resources/Photos/ttest_all.png)

![ttest_lot1.png](/Resources/Photos/ttest_lot1.png)

![ttest_lot2.png](/Resources/Photos/ttest_lot2.png)

![ttest_lot3.png](/Resources/Photos/ttest_lot3.png)

The p-value for all lots is 1, indicating that there is no significant difference between the PSI measurements for the different lots. This means that the hypothesis is supported by the data from all lots. However, the p-value for Lot3 is less than 0.05, indicating that there is a significant difference in the PSI measurements for this lot, and the hypothesis is rejected for this lot. This suggests that there may be some factors that are affecting the PSI measurements in Lot3, and further investigation may be needed to understand the reasons for this.



## Deliverable 4: Mecha Car Versus Competiton

Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
In your description, address the following questions:

Q: What metric or metrics are you going to test?
- Cost
- Horsepower 
- MPG/Fue Efficiency 

Q: What is the null hypothesis or alternative hypothesis?
A: The null hypothesis states that MechaCar's fuel efficiency is affected by weight in the same way as the fuel efficiency of its competitors is affected by weight. This hypothesis assumes that the relationship between weight and fuel efficiency is similar for MechaCar and its competitors. In other words, if one increases, the other is also expected to increase or decrease in a similar manner.

Q: What statistical test would you use to test the hypothesis? And why?
A: A two sample t-test is a statistical test used to determine the significance of the difference between the means of two groups.

Q: What data is needed to run the statistical test?
A: To compare the fuel efficiency of MechaCar and its competitors, we would need to collect data on the average mpg for multiple trips with the same weight being carried for both MechaCar and its competitors. This would allow us to compare the fuel efficiency of MechaCar with that of its competitors and determine if there is a significant difference between the two.