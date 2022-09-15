# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

![## Linear Regression to Predict MPG](https://user-images.githubusercontent.com/107209737/190477429-a5b830a1-a565-407b-933f-2a78e1f312f4.png)

### 1) Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
- Vehicle Weight (0.0776)
- Spoiler Angle (0.3069)
- AWD (0.1852)
### 2) Is the slope of the linear model considered to be zero? Why or why not?
- The slope of the linear model is not considered to be zero because the p-value is less than 0.05.
### 3) Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
- The R-squared value is 0.7149. That means the model would predict the mpg of the MechaCar correctly 71% of the time. This means that the             model would be considered effective.

## Summary Statistics on Suspension Coils
### Lot Summary Table
![lot_summary](https://user-images.githubusercontent.com/107209737/190483643-d72c9107-b6da-474c-b2e8-ef46a3eb9848.png)

### Total Summary Table
![total_summary](https://user-images.githubusercontent.com/107209737/190483654-ed8d333c-9708-4e83-b845-3713851f026f.png)

### 4) The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
- The varience is about 62.29 PSI for total summary. Lot 1 is about 0.98, lot 2 is about 7.47, and lot 3 is about 170.29. Therefore, the first two lots meet the design specifications. However, the third lot does not because ot exceeds the design specifications by more than double.


