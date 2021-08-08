# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
According to the statistics analysis we find that groun clearance and vehicle length provide a non-random amount of varience to the mpg values in the dataset. The Pr(>|t|) value for ground clearance is 5.77e-08 and the Pr(>|t|) value for  length is 2e-16. Being that both of these number are far less then 0.05 we can with a fair amount of confidence fail to reject the null hypothesis. As for the slope, we find that the length to Mpg ratio to be 6.26 which is much larger then zero. A less significant slope was the relationship between ground_clearance vs mpg which  showed a ratio of 3.56. The closest value to zero was vehicle_weright at about 1.24e-03. The overall Linear Regression model has a P value of 5.35e-11 which is below the 0.05. With that we can safely assume that the model stands a good chance at predicting Mpg for MechaCar prototype project.  

![Linear Regression to Predict MPG](https://github.com/Hamza97anh/MechaCar_Statistical_Analysis/blob/623a8dd193dcfef882a8d4b3048700cb6d8afaa1/Images/Linear%20Regression%20to%20Predict%20MPG.PNG)

## Summary Statistics on Suspension Coils

For this summary we want to answer whether the current lot of suspension struts are withing manufacturing specifications. The factory dictates that the there must not be more then 100 psi in variance. According to the total summary we see that the Mean was 1499  with a varience of about 62 psi. The Standerd deviation is 7.89. 

![total_summary](https://github.com/Hamza97anh/MechaCar_Statistical_Analysis/blob/857d1b9011784c7a406db1788f5950b1b91bf3b0/Images/total_summary.PNG)

Looking at the Lot Summary we see a similar picture. As a whole all three lots passeed the quality control test with Lot 1 and 2 being way less then 10 psi in variance. However Lot 3 while still being in the clear, showed a much higher variance then the rest at 170 psi in variance. That number is much higher then the allowed variance so lot 3 would have to have to be rejected from going into a final product. 

![lot_summary](https://github.com/Hamza97anh/MechaCar_Statistical_Analysis/blob/857d1b9011784c7a406db1788f5950b1b91bf3b0/Images/lot_summary.PNG)
