# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

<img width="511" alt="MechaCar MPG Linear Reg" src="https://user-images.githubusercontent.com/107484694/196108515-2c42366b-c19c-40f5-a40c-675cf6320c21.png">

Vehicle length and ground clearance are statistically unlikely to provide random amounts of variance to the linear model. In other words, vehicle length and ground clearance have a significant impact on MechaCar prototype's MPG. 

The slope of the linear model is not considered to be zero. The p-value of 5.35e-11 is smaller than the assumed significance level of 0.05% which indicates that there is sufficient evidence to reject the null hypothesis. 

This linear model does not predict the mpg of MechaCar prototypes effectively. The R-squared value of 0.7149 means that nearly 71% of all mpg predictions will be determined by this model. In scientific studies, the R-squared may need to be above 0.95 for a regression model to be considered reliable.

## Summary Statistics on Suspension Coils
All manufacturing lots:

<img width="344" alt="Total Summary" src="https://user-images.githubusercontent.com/107484694/196121789-56cb5ecf-cb59-4238-a798-6791bac25f59.png">

Individual lots:

<img width="498" alt="Lot Summary" src="https://user-images.githubusercontent.com/107484694/196121857-b49bc5ff-178e-405c-8d7a-2adef2b837b4.png">

The current manufacturing data meets the design specification for all manufacturing lots in total as the variance is 62.29 PSI which is within the 100 PSI variance requirement. 

Looking at the individual lots, Lots 1 and 2 are within the 100 PSI variance requirement while Lot 3 is showing much larger variance at 170.29. 

## T-Tests on Suspension Coils

The t-test across all manufacturing lots revealed:

<img width="403" alt="ttest all lots" src="https://user-images.githubusercontent.com/107484694/196289691-d6fe4824-cc0a-4341-901e-2162cd7bddcc.png">

The p-value is 0.06 which can allow us to conclude that there is not enough evidence to reject the null hypothesis. In other words, the mean of all manufacturing lots is statistically similar to the population mean of 1500 pounds per square inch. 

The t-tests for lots 1, 2, and 3 showed: 

<img width="403" alt="ttest lot 1" src="https://user-images.githubusercontent.com/107484694/196290793-89531300-d370-470e-ae9c-4881f40577ac.png">

<img width="403" alt="ttest lot 2" src="https://user-images.githubusercontent.com/107484694/196290819-c462e249-b2a2-43d1-9bac-4d37fb361fcf.png">

<img width="403" alt="ttest lot 3" src="https://user-images.githubusercontent.com/107484694/196290832-797498d4-f6e8-40f3-a744-770a420eabad.png">

The sample means of lots 1 and 2 are 1500 and 1500.2 with p-values of 1 and 0.61 respectively. This shows that there is no statistical difference between the sample means of the two lots and the population mean of 1500.

Lot 3 has a mean of 1496.14 with a p-value 0.042 which indicates that the two means are statistically different and to reject the null hypothesis. 

## Study Design: MechaCar vs Competition

This statistical study will investigate MechaCar's dependability in comparison to the dependability of vehicles from other manufacturers. 

What metric or metrics will be tested?

Annual Maintenance Cost: Independent Variable
Safety Feature Rating: Independent Variable 
Engine Type: Independent Variable 
Vehicle Class: Independent Variable
MPG: Independent Variable
Vehicle Lifespan: Dependent Variable

What is the null hypothesis or alternative hypothesis?

Null Hypothesis (Ho): The vehicle lifespan of MechaCar is correctly based on the vehicle's dependability metrics.
Alternate Hypothesis (Ha): The vehicle lifespan of MechaCar is not correctly based on the vehicle's dependability metrics.

Statistical Test

Multiple linear regression would be best in determining the statistical relationship between vehicle lifespan (dependent variable) and the vehicle dependability metrics (independent variables). The data needed to run this test includes the average vehicle lifespan (miles or years) and the values for each other independent variables.

