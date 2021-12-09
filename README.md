# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![Linear Regression mpg](https://user-images.githubusercontent.com/87910875/145454872-62172b81-9234-40ef-8f04-c7f06845248a.png)


Vehicle weight, spoiler angle, and AWD are the coefficients that provided a non-random amount of variance. Vehicle length and ground clearance provided a random amount of variance to the mpg values.

The slope of the model will not be zero since vehicle weight, spoiler angle, and AWD affected the independent variable of MPG. The slope will be considered 0 if none of the coefficients affected MPG.

Although not very accurate, the model can be used to predict the MPG of prototypes due to the R-squared being .71 which is accurate about 71% of the time.

## Summary Statistics on Suspension Coils

### Total Summary: 

![total summary](https://user-images.githubusercontent.com/87910875/145457731-1d3e617a-1523-4d6a-b396-81d79d90a50e.png)

### Lot Summary: 

![lot summary](https://user-images.githubusercontent.com/87910875/145457744-dae99db9-637d-4cec-96a9-5184172d87cb.png)

The overall variance of PSI in the image above is 62.2 which is below the 100 PSI limit. The variance of PSI's for lots 1 and 2 are below the limit but the variance of the third lot is well over the limit. 

## T-Tests on Suspension Coils

### Overall t-test:
![t-test](https://user-images.githubusercontent.com/87910875/145485972-8d1724a8-3378-42ba-8dc3-84bc2d5bf634.png)

Although the sample mean is about 94% accurate, it is not statistically significant since the p-value is greater than .05. If the level of confidence is 95%, we will now fail to reject the null hypothesis.

### Lot 1 t-test:

![lot1 t-test](https://user-images.githubusercontent.com/87910875/145487692-1844e74d-ad8e-4955-85c0-71e94cf08ae0.png)

The p-value for the t-test of lot 1 is 1 meaning that is statistically significant and we will reject the null hypothesis. 

### Lot 2 t-test

![lot2 t-test](https://user-images.githubusercontent.com/87910875/145487981-c806d736-0e92-4135-a07e-eb2e1e7fad00.png)

The p-value for lot 2 is .6 and we will fail to reject the null hypothesis if would confidence interval is 95% since it is not statistically significant.


### Lot 3 t-test

![lot3 t-test](https://user-images.githubusercontent.com/87910875/145488194-9df3d512-c937-437e-83af-66dd3d808da3.png)

The p-value for lot 3 is .04 and we will reject the null hypothesis since it is statistically significant. 

## Study Design: MechaCar vs Competition

The metric I would like to test is how vehicle size and MPG are correlated. My null hypothesis is that vehicles over 3500lbs are less fuel-efficient than vehicles over 3500lbs. I would use a simple linear regression since I am testing for correlation. The data needed is various weights of vehicles for the independent variable and their fuel efficiency as the dependent variable.
