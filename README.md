# MechaCar_Statistical_Analysis
## Devin Monsen
### 11/08/2022
---
## Linear Regression to Predict MPG
![linreg](https://github.com/DevinJaxues/MechaCar_Statistical_Analysis/blob/f275aa921236cd7c5707ac6b9d790ab5641ee9e1/LinReg.PNG)
---
- We can see that vehicle length and ground clearance are the two main variables that affect MPG due to p values being under .05.
- With knowing that our p value is below .05 this also clearly shows us that the slope is not 0.
- At the bottom you can see our R-squared value is 0.7149 showing that our model is capable of predicting MechaCar prototype MPG.
---
## Summary Statistics on Suspension Coils
![lotsum](https://github.com/DevinJaxues/MechaCar_Statistical_Analysis/blob/d3902ab0e7dd33f218d6869ff190e89c2e3e2d16/lotsum.PNG)
![totalsum](https://github.com/DevinJaxues/MechaCar_Statistical_Analysis/blob/d3902ab0e7dd33f218d6869ff190e89c2e3e2d16/totalsum.PNG)
---
- PSI variance comes to 62.29 which is accecptable for our 100lbs. PSI for all of the manufacturer lots.
---
## T-Tests on Suspension Coils
![ttest](https://github.com/DevinJaxues/MechaCar_Statistical_Analysis/blob/d3902ab0e7dd33f218d6869ff190e89c2e3e2d16/ttest.PNG)
---
- After the t-test on the SuspesionPSI we got our p-value of 0.06028 and an alternative hypothesis that the true mean is not equal to 1500. Although this is suboptimal, the low p-value isnt too low. T-test for lot 1: mean = 1,500 and p-value = 1 which makes this a statistical match. Lot 2: mean = 1,498 and p-value .06 which also matches. But lot 3 had a mean = 1,496 and p-value of .04 which falls below .05 which makes it different from the other lots.
