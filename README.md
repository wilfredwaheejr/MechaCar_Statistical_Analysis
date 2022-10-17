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

The current manufacturing data meets the design specification for all manufacturing lots in total as the variance isi 62.29 PSI which is within the 100 PSI variance requirement. 

Looking at the individual lots, Lots 1 and 2 are within the 100 PSI variance requirement while Lot 3 is showing much larger variance at 170.29. 
