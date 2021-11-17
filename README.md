# MechaCar_Statistical_Analysis
Analysis of automotive manufacturing

Deliverable 1
![Alt Text](https://github.com/CarlosRello/MechaCar_Statistical_Analysis/blob/main/Resources/Mech_stat.png)

1.- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

- The Pr(>|t|), of the variables greater than 5%, indicates that these variables have a low level of statistical significance of a regression coefficient.

- Vehicle_weigth
- spoiler_angle
- AWD

Is the slope of the linear model considered to be zero? Why or why not?

The p-value of the model is 5.35e-11, which is much lower than the assumed significance level of 0.05%. Therefore, the slope of the model is not zero.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

Yes it does, The model has a multiple R-squared of 0.7149, which tells us that it is 71.49% that this model can be explained by the predictor variables

## Summary Statistics on Suspension Coils

![Alt Text](https://github.com/CarlosRello/MechaCar_Statistical_Analysis/blob/main/Resources/Total_summary.png)

![Alt Text](https://github.com/CarlosRello/MechaCar_Statistical_Analysis/blob/main/Resources/lot_summary.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

- The variance across all the lots does not exceed the 100 pound per square inch variance, although when analyzing the individual lots, Lot 3 presents a higher variance than the expected 100 PSI with a total of 170.29.

## T-Tests on Suspension Coils

![Alt Text](https://github.com/CarlosRello/MechaCar_Statistical_Analysis/blob/main/Resources/t-test.png)

![Alt Text](https://github.com/CarlosRello/MechaCar_Statistical_Analysis/blob/main/Resources/t-test_subset.png)

Only when measuring the Lot 3 mean PSI difference to the 1500 population standard, provided a lower mean value. Statistical significance difference was observed, therefore rejecting null hypothesis.

