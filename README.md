# MechaCar_Statistical_Analysis

## Deliverable 1 - Linear Regression to Predict MPG

* What we found was that vehicle length and ground clearance demonstrated a significant random variance impact on MPG. On the flipside, vehicle weight, spoiler angle and AWD showed non-random variance. 

* The p-value we came up with is significantly smaller than the benchmark of 0.05 to designate statistical signifance, and therefore we cannot reject the null hypothesis. 

* Our R value for this analysis is approximately 71%. What this means for our analysis is that ~71% of the time the model will predict mpg values correctly.

<img width="621" alt="Screen Shot 2021-01-22 at 7 32 45 PM" src="https://user-images.githubusercontent.com/68168883/105571202-2ff53a80-5d1c-11eb-930f-905836bd92a9.png">

<img width="624" alt="Screen Shot 2021-01-22 at 7 32 59 PM" src="https://user-images.githubusercontent.com/68168883/105571206-34215800-5d1c-11eb-8f4f-e91b4c930b05.png">

## Deliverable 2 - Summary Statistics on Suspension Coils

* The design specifications for the MechaCar suspension coils dictates that variance of the suspension coils cannot exceed 100 pounds per square inch. From our analysis it appears that we meet this criteria.  

<img width="334" alt="Screen Shot 2021-01-22 at 8 14 13 PM" src="https://user-images.githubusercontent.com/68168883/105571289-e35e2f00-5d1c-11eb-8f38-21ea8dd2db08.png">

* When we look at lots 1-3, it is very clear that lot 3 has an extreme amount of variance that exceeds the criteria that are required. On the otherhand, lots 1-2 fall within the parameters that we were asked for.

<img width="637" alt="Screen Shot 2021-01-22 at 8 31 31 PM" src="https://user-images.githubusercontent.com/68168883/105571346-48b22000-5d1d-11eb-9567-22258857cb8b.png">

## Deliverable 3 - T-Test on Suspension Coils

This first image shows our T-Test conducted across all lots

<img width="622" alt="Screen Shot 2021-01-22 at 7 49 07 PM" src="https://user-images.githubusercontent.com/68168883/105571409-9464c980-5d1d-11eb-8f2e-00dae0e38939.png">

The next image shows our T-Test conducted for lot 1

<img width="622" alt="Screen Shot 2021-01-22 at 7 49 19 PM" src="https://user-images.githubusercontent.com/68168883/105571460-f6bdca00-5d1d-11eb-8365-7f65292d34cb.png">

Next we look at the T-Test for lot 2

<img width="621" alt="Screen Shot 2021-01-22 at 7 49 33 PM" src="https://user-images.githubusercontent.com/68168883/105571464-fa515100-5d1d-11eb-98c1-d6b8b2a6fee8.png">

And finally we look at the T-test that was done for lot 3

<img width="621" alt="Screen Shot 2021-01-22 at 7 49 47 PM" src="https://user-images.githubusercontent.com/68168883/105571466-fe7d6e80-5d1d-11eb-8650-7b051613c449.png">

Based on our p-values for lots 1-3, we are unable to reject the null hypothesis and thus the true mean could in fact be 1500 psi. 

## Deliverable 4 - MechaCar vs Competition

* For people who know a lot about cars and even for those that don't, there are few things that seem to resonate more than horsepower and and miles per gallon. It seems ingrained that we not only want a super powerful car but an efficient one as well and so these 2 metrics would seem to be ones that potential purchasers would be interested (whether rightly or not is a separate issue). Given the focus on the environment, miles per gallon would be a metric that would directly be attributed to fuel effiency and, for lack of better words, greenness. 

* Our null hyptohesis would state that: the statistical difference between the horsepower provided by the MechaCar would not be stastically significant from the competition.
* The alternative hypothesis would state that: in fact there is NOT a statsistical significantly difference between the MechaCar and its competitors with regards to horsepower. 
* The test we would run to examine statistical significance would be a T-test because we are looking at 2 specific categorical metrics. 

* The next thing we want to consider is fuel efficiency for these cars. 

* Our null hypothesis would state that: the mean fuel efficiency between the MechaCar and its competitors is not significantly different.
* The alternative hypothesis would state that: in fact the mean fuel efficiency between the MechaCar and its competitors is in fact significantly different.
* To test this hypothesis, I believe that an ANOVA test would provide us with the best results because we must consider a variety of factors and thus, an analysis of the variance would appear to be the most fitting. 
