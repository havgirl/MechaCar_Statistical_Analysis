# MechaCar_Statistical_Analysis

## Objective
In this challenge we are assisting the AutosRus data analytics team to review production data for insights that may help the manufucturing team overcome troubles encountered by their newest prototype, the MechaCar.

These activities include the following:
- Linear regression analysis to predict mpg
- Statistics on Suspension Coils/PSI
- Comparison of manufacturing lots vs the mean population
- A study design to futher compare MechaCar vehicles against vehicles from other manufactures

### Linear Regression to Predict MPG

![](Images/Module16.1c.png)

**After completing the linear regression analysis, AutoRus requested a response to the following questions.**

**Q1. Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**

*A1. The strongest contributors of non-random variances include:*
- *Vehicle length - p-value 2.60e-12*
- *Ground clearance - p-value 5.21e-08*

**Q2. Is the slope of the linear model considered to be zero? Why or why not?**

*A2. The p-value for this model, 5.35e-11, is much smaller than the assumed significance level of 0.05% which indicates there is evidence to reject the null hypothesis, and that the slope of the linear model is not zero.*

**Q3. Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**

*A3. The r-squared value of 0.7149 indicates the model has good predictive power for mpg, and that approximately 71% of all mpg predictions will be determined.*

### Summary Statistics on Suspension Coilds

![](Images/Module16.2a.png)
![](Images/Module16.2b.png)

**After completing the summary statistics, AutoRus requested we address the following question.

**Q1. The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specticiation for all manufacturing lots in total and each lot individually? Why or why not?**

*A1. Although the total summary indicates a variance of 62.29356 which falls within the allowed threshold, it is imperative that each lot is reviewed individually.  Here, we see concern especially in Lot Three, which indicates a variance of 170 PSI and therefore does not meet the maximum variance requirement.*

### T-Tests on Suspension Coils

![](Images/Module16.3a.png)
![](Images/Module16.3b.png)
![](Images/Module16.3c.png)
![](Images/Module16.3d.png)

**After completing the summary and lot tests on the suspension coils, AutoRus requested we summarize our interpretation and finding for the results, which follow.**

- *Test 1 sample has a p-value of 1, which means there is no statistical difference between the sample mean and the presumed population mean, thererefore we cannot reject the null hypothesis.*
- *Test 2 - Lot 1 has a p-value of 1.568e-11 which indicates there is a higher probability of occurance using the null hypothesis which cannot therefore be rejected.*
- *Test 3 - Lot 2 has a sample mean of 1500.2, and a p-value of .0005, which is lower than the common significance level of .05.  This indicates to reject the null hypothesis that the sample and population means are not statistically different.*
- *Test 4 - Lot 3 has a sample mean of 1496.14, and a p-value of .1589; therefore the null hypothesis cannot be rejected.*

### Design Study Comparing the MechaCar to the Competition

**In addition to assisting with the above analytics, AutoRus requested we design a statistical study to compare performances of the MechaCar vehichles against performance of vehicles against other manufacturers.  A few metrics that would be of interest to a consumer include cost, city/highway fuel efficiency, horsepower, maintenance or saftey ratings.  Upon completion the following questions should be answered:**

**Q1. What metric or metrics are you going to test?**

*A1.   *

**Q2. What is the null hypothesis or alternative hypothesis?**

*A2.   *

**Q3. What statistical test would you use to test the hypothesis? And why?**

*A3.   *

**Q4. What data is needed to run the statistical test?**

*A4.  *


