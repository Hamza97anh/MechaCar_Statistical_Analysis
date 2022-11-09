# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG
According to the statistics analysis we find that ground clearance and vehicle length provide a non-random amount of varience to the mpg values in the dataset. The Pr(>|t|) value for ground clearance is 5.77e-08 and the Pr(>|t|) value for  length is 2e-16. Being that both of these number are far less then 0.05 we can with a fair amount of confidence fail to reject the null hypothesis. As for the slope, we find that the length to Mpg ratio to be 6.26 which is much larger then zero. A less significant slope was the relationship between ground_clearance vs mpg which  showed a ratio of 3.56. The closest value to zero was vehicle_weright at about 1.24e-03. The overall Linear Regression model has a P value of 5.35e-11 which is below the 0.05. With that we can safely assume that the model stands a good chance at predicting Mpg for MechaCar prototype project.  

![Linear Regression to Predict MPG](https://github.com/Hamza97anh/MechaCar_Statistical_Analysis/blob/623a8dd193dcfef882a8d4b3048700cb6d8afaa1/Images/Linear%20Regression%20to%20Predict%20MPG.PNG)

## Summary Statistics on Suspension Coils

For this summary we want to answer whether the current lot of suspension struts are within manufacturing specifications. The factory dictates that the there must not be more then 100 psi in variance. According to the total summary we see that the mean was 1499  with a varience of about 62 psi. The Standerd deviation is 7.89. 

![total_summary](https://github.com/Hamza97anh/MechaCar_Statistical_Analysis/blob/857d1b9011784c7a406db1788f5950b1b91bf3b0/Images/total_summary.PNG)

Looking at the Lot Summary we see a similar picture. As a whole all three lots passeed the quality control test with Lot 1 and 2 being way less then 10 psi in variance. However Lot 3 while still being in the clear, showed a much higher variance then the rest at 170 psi in variance. That number is much higher then the allowed variance so lot 3 would have to have to be rejected from going into a final product. 

![lot_summary](https://github.com/Hamza97anh/MechaCar_Statistical_Analysis/blob/857d1b9011784c7a406db1788f5950b1b91bf3b0/Images/lot_summary.PNG)

## T-Tests on Suspension Coils

A t-test was conducted on the manufacturing lots of Suspension Coils to determine if the mean was statistically different then the 1500 psi projected figure. The test p-value showed a 0.06 which is 0.01 above the 0.05 limit. Our range was from 1497.507 to 1500.053 with a sample mean of 1498.78. We can say that givin the marginal diffrences in values that there is no statistical difference from the population mean of 1500 pounds per inch.

![One_Sample_Test](https://github.com/Hamza97anh/MechaCar_Statistical_Analysis/blob/e08a285c691d29367c07eab235d51c2e8dac2002/Images/One_Sample_Test.PNG)

For sample size Lot 1, our test showed a p-value of 1, confidence interval of 95% (1499.719, 1500.281), and sample mean of exactly 1500. The sample mean is not significantly different from the population mean and we fail to reject our null hypothesis.

![Lot_1_Test](https://github.com/Hamza97anh/MechaCar_Statistical_Analysis/blob/e08a285c691d29367c07eab235d51c2e8dac2002/Images/Lot_1_Test.PNG)

For sample size Lot 2, our test showed a p-value of 0.6072 which is more then the 0.05 limit for our P value. Our confidence interval was 95% exactly the same as lot 1 at a range of (1499.423, 1500.977), and a sample mean of about 1500.2. With a difference that small we can safely fail to reject our null hypothesis. 

![Lot_2_Test](https://github.com/Hamza97anh/MechaCar_Statistical_Analysis/blob/e08a285c691d29367c07eab235d51c2e8dac2002/Images/Lot_2_Test.PNG)
Lot 3 had a p-value of 0.04168 which is smaller than our 0.05 minimum. This data set also shows a 95 percent confidence interval that is below the population mean with a range of (1492.431, 1499.849) and a sample mean of 1496.14. Because of this we can reject our null hypothesis and say that the sample mean of Lot 3 is significantly different from the population mean of 1500.

![Lot_3_Test](https://github.com/Hamza97anh/MechaCar_Statistical_Analysis/blob/e08a285c691d29367c07eab235d51c2e8dac2002/Images/Lot_3_Test.PNG)

## Study Design: MechaCar vs Competition

This study is intended to help predict the reliablity and the marketablity of the MechaCar vs the competition. The MPG study was intended to maximize the marketablity of the car. Many consumers today prioritieze MPG when shopping for a daily driven vehicle. The reliablity study goes beyond the MechaCar itself because reliablity reflects on the image of the whole compnay. The success of the MechaCar when it comes to reliabliilty will help boost the sales of future products as people start to consider MechaCar to be a manufacturer of relialbe cars. Those factors help in the resale value of the vehicle as depreciation and reliablity tends to have a negative relationship. The more relaible a car the less depreciation. Customers will feel more confident in their buying decision as they will feel their money is more secure with MechaCar compared to the rest of the comptition. Most major manufacturers tend to make their new products based on previous products. This helps them prevent production costs but also it allows them to improve on a previous tested deign as opposed to something completely untested. As data analysits, we can look at the failiuer rate of the previous model vs. the competition and understand how we compare to the rest of the market. Our null hypothesis, The longetivity of a Mechacar is equal to the longetivity of other car manufacturers. The alternate hypothesis, The longetivity of a Mechacar is longer than or not equal to that of other car manufacturers. Because we are going to be comparing means of a continuous numerical variable across a number of different manufacturers, we will opt for a one-way ANOVA test. To do this we will need data that shows the longevity of MechaCar vs two or more brands to compare. 

