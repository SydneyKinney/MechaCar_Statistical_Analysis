# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![## Linear Regression to Predict MPG](https://user-images.githubusercontent.com/107209737/190477429-a5b830a1-a565-407b-933f-2a78e1f312f4.png)

#### 1) Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Vehicle Weight (0.0776)
- Spoiler Angle (0.3069)
- AWD (0.1852)
#### 2) Is the slope of the linear model considered to be zero? Why or why not?
- The slope of the linear model is not considered to be zero because the p-value is less than 0.05.
#### 3) Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- The R-squared value is 0.7149. That means the model would predict the mpg of the MechaCar correctly 71% of the time. This means that the             model would be considered effective.

## Summary Statistics on Suspension Coils
### Lot Summary Table
![lot_summary](https://user-images.githubusercontent.com/107209737/190483643-d72c9107-b6da-474c-b2e8-ef46a3eb9848.png)

### Total Summary Table
![total_summary](https://user-images.githubusercontent.com/107209737/190483654-ed8d333c-9708-4e83-b845-3713851f026f.png)

#### 4) The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- The varience is about 62.29 PSI for total summary. Lot 1 is about 0.98, lot 2 is about 7.47, and lot 3 is about 170.29. Therefore, the first two lots meet the design specifications. However, the third lot does not because ot exceeds the design specifications by more than double.

## T-Tests on Suspension Coils
The manufacturing lots and each lot individually are not statistically different from the population mean of 1,500 pounds per square inch. All lots had a mean of 1498.78. Lot 1 had a mean of 1500. Lot 2 had a mean of 1500.2. Lot 3 had a mean of 1496.14. 

### All lots results
![All_Lots](https://user-images.githubusercontent.com/107209737/190486913-119bcf6a-7426-4ae5-9c55-baf095583e0c.png)

### Lot 1 results
![Lot1Test](https://user-images.githubusercontent.com/107209737/190486916-2e6c1e13-7517-426e-9719-4db8caa01bbf.png)

### Lot 2 results
![Lot2Test](https://user-images.githubusercontent.com/107209737/190486918-0b9c5fd2-ef83-404d-be6c-543cbccdb905.png)

### Lot 3 results
![Lot3Test](https://user-images.githubusercontent.com/107209737/190486921-9db0a884-f556-4029-be1e-43d2f5c2cf00.png)

## Study Design: MechaCar vs Competition
