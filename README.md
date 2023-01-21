# MechaCar

## Linear Regression to Predict MPG
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
  - Vehicle weight, spoiler_angle & AWD provided a non-random amount of variance. Variables ground_clearance and    vehicle_length had the most amount of random variance. 
Is the slope of the linear model considered to be zero? Why or why not?
  - The slope cannot be zero as the p-value is < 0.05 . 
Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
  - Multiple R-squared:  0.7149 (71%) ,	Adjusted R-squared:  0.6825 (68%). The model predicts 71% of the mpg of MechaCar prototype.


## Trip Analysis
* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
  - From the summary, it appears that Lot 1 and 2 are within the design specifications. However, the variance is quite high in Lot 3 and exceeds the manufacturing specifications.  

## T-Tests on Suspension Coils

# all 3 lots:
![image](https://user-images.githubusercontent.com/112893464/213878228-f497e9a8-542c-445a-b91f-00381e5933e2.png)
