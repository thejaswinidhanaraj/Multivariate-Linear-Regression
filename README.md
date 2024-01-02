# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
Import panda
<br>

### Step2
Import linear model for sklearn
<br>

### Step3
Read the file cars.csv
<br>

### Step4
Assign the values for x and y as required
<br>

### Step5
Create the linear regression model and predict the output
<br>

## Program:
```
#Developed by: THEJASWINI
#Reference Number: 212223110059
import pandas as pd
from sklearn import linear_model
df=pd.read_csv('cars (1).csv')
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("coefficient",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))

```
## Output:
![image](https://github.com/thejaswinidhanaraj/Multivariate-Linear-Regression/assets/148514511/e705726b-2738-4895-9165-44abfca157da)



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
