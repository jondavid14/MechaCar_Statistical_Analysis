
## Project Overview
The goal of the project is to analyze the data given about the car manufactures and test if there is any correlation
## Linear Regression to Predict MPG
![Linear Regression](https://github.com/jondavid14/MechaCar_Statistical_Analysis/blob/main/Resources/linear_regression_summary.PNG)

3 Key Takeaways:
the intercept, vehicle_length, and ground_clearance coeeficients can be said to provide a non-random amount of variance to the mpg values. 
At a significance level of 0.05, we are able to reject the null hypothesis because of the extremely small p-value. When it falls out of the 95% significance nthen we can prove or reject the null hypothesis


## Summary Statistics on Suspension Coils
<p align="center">
<img src = "https://github.com/jondavid14/MechaCar_Statistical_Analysis/blob/main/Resources/total_summary_table.PNG" width="410" height="70"/>
<img src = "https://github.com/jondavid14/MechaCar_Statistical_Analysis/blob/main/Resources/lot_summary_table.PNG" width="500" height="110"/>
</p>

The overall variance for the entire dataset indicates that the current manufacturing data meets the 100 pounds per square inch variance limitation. 
with the high variance this shows it is random, and the third may be random and not meet the requiremnt.

## T-Test on Suspension Coils
### T-Test on Entire Lot
<p align="center">
<img src="https://github.com/jondavid14/MechaCar_Statistical_Analysis/blob/main/Resources/t-test.PNG">
</p>
At a significance level of 0.05, we fail to reject the null hypothesis since the p-value equals 0.06. Therefore we cannot reject the null hypothesis
### T-Test on Three Smaller Lots
<p align="center">
<img src="https://github.com/jondavid14/MechaCar_Statistical_Analysis/blob/main/Resources/lots_t_test.PNG">
</p>
#### Lot 1
At a significance level of 0.05, we fail to reject the null hypothesis since the p-value equals 1.
#### Lot 2
At a significance level of 0.05, we fail to reject the null hypthesis again since the p-value equals 0.6072. The second lot also has a relatively small confidence interval.

#### Lot 3
At a significance level of 0.05, we can reject the null hypothesis since the p-value equals 0.04168. 

## Study Design: MechaCar vs. Competition
Another statistical study that can be performed to determine MechaCar's standing against its competition is a linear regression on city and highway fuel efficiency. Gasoline is expensive nowadays, and it is an important feature that many consumers look at when purchasing a new car. The metrics that can be included in this analysis are:
* City and highway fuel efficiency: dependent variable
* Horse power: independent variable
* Vehicle weight: independent variable
* AWD capabilities: independent variable
* MPG: independent variable
In addition to the MPG, AWD, and vehicle weight data that we already have, we would have to collect fuel efficiency and horse power data for the sample data set at hand.
