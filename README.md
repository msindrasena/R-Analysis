# R-Analysis

This is a statistical analyisis on specific vehicle specs that impact miles per gallon. It also 
includes weight capacity of multiple suspension coils to see if the manufacturing process is 
consistent among all lots.

After conducting a summary of coefficients, vehicle length and ground clearance were shown to 
provide non-random variance to mpg sets as they all had a p-value of less than .05. 
Length:2.60e-12  Ground Clearance: 5.21e-08

Spoiler Angle, AWD and Spoiler Weight have influence when predicting the MPG. 

When looking at the relationship between variables and mpg, we can see that value of
Multiple R-Squared is .7149 and  P-Value is 5.35e-11. This implies a strong positive linear 
relationship and also indicates a low significance level. Therefore, we can reject the null
hypothesis as there is sufficient statistical evidence that the null hypothesis is not true. 

![](https://github.com/msindrasena/R-Analysis/blob/master/Images/Variables%20and%20Mpg.PNG)

The slope of the model is not 0. This model does not predict mpg of MechaCar prototypes effectively
as there are other factors playing a role in mpg when looking at the p-value of the y-intercept. 

A table was created summarizing statistical data such as the mean, median, variance, and standard 
deviation of weight capacity for suspension coils. (Seen below):

![](https://github.com/msindrasena/R-Analysis/blob/master/Images/Suspension%20Coil%20Statistics.PNG)

As the design specifications for MechaCar suspension coils calls for a variance 
no more than 100 pounds per inch, we can see that Lot 1 and 2 are within the boundaries,
but Lot 3 is at 220, which means they are not producing the suspension coils accurately. 

![](https://github.com/msindrasena/R-Analysis/blob/master/Images/Summary%20Statistics%20by%20Lot.PNG)

A t-test was conducted to determine if the suspension coil's pound per inch results
are statistically different from the mean population results of 1,500 pounds per inch. 
The p value= .5117 which means we do not have sufficient evidence to reject the null
hypothesis indicating that the means are statistically similar.

![](https://github.com/msindrasena/R-Analysis/blob/master/Images/T-Test.PNG)

Some of the factors that consumers consider when buying a vehicle are miles per gallon,
fuel economy/efficiency, price, space, safety, design and comfort. 

As more consumers are looking to go green and lower their carbon footprint, 
a study could test if MechaCar's fuel efficiency matches the industry's standard and if 
price matches the industry standard. 

A multiple regression analysis using ANOVA could be conducted to see if there is a difference between the sample
 mean and the population mean of other vehicles in the industry for fuel efficiency and a t-test 
could be used to test cost. 

