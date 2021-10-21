# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

Vehicle weight, AWD and spoiler_angle provided a non-random amount of variance. 

- Is the slope of the linear model considered to be zero? Why or why not?

Slope is not zero just by looking at the p-value, which is less than 0.05.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

More likely it will than it will not. R-squared value is 71%, that means 71% of the time, it will predict the values of mpg correctly. 



## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

Lot 1 and Lot 2 are both within design specifications and have almost the same exact mean and median. Lot 3 shows the most variance and exceeds the manufacturers specs.

## T-Tests on Suspension Coils

Lot 1 and Lot 3 the PSI values are not different from the population mean. lot 2 the p-value is .347. Shows evidence that the suspension coil is different from the population mean. T-tests results:

<img width="546" alt="Screen Shot 2021-10-21 at 12 11 34 AM" src="https://user-images.githubusercontent.com/86085982/138215626-df584ff3-8e3c-48f9-ae17-fdebf04a199b.png">

<img width="546" alt="Screen Shot 2021-10-21 at 12 12 05 AM" src="https://user-images.githubusercontent.com/86085982/138215723-de68f749-2653-4a05-a5d4-d7858f49210d.png">

<img width="546" alt="Screen Shot 2021-10-21 at 12 12 27 AM" src="https://user-images.githubusercontent.com/86085982/138215768-516b41cc-cb58-4e16-a372-b15f92e3ba95.png">

<img width="546" alt="Screen Shot 2021-10-21 at 12 12 40 AM" src="https://user-images.githubusercontent.com/86085982/138215790-421180e7-829f-4fcb-8d5b-3e3317ef8388.png">




## Study Design: MechaCar vs Competition
Horsepower is a feature that consumers look into when buying a car. You can use tests to see if the MechaCar is different from the competition using that factor. 
Using a t-test could help with collecting data from different types of competitor vehicles. Would compare the population of all types of competitor vehicles.


