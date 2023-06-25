# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br> import pandas as pd

### Step2
<br> Read the csv file.

### Step3
<br>
Get the value of X and y variables.
### Step4
<br>
Create the linear regression model and fit.
### Step5
<br>
predict the CO2 emission of a car where the weight is 2300kg, and the volume is 1300cm3.

Step6 : Print the predicted output.
## Program:
```
#Developed by : rohit g
#Register Number : 212222240083
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars (1).csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient:",regr.coef_)
print("Intercept:",regr.intercept_)
print("Amount:",regr.predict([[3300,1300]]))


```
## Output:

### Insert your output
![image](https://github.com/rohitgunasekaran/Multivariate-Linear-Regression/assets/119404546/566c99b8-5e24-426c-8dbe-2c0b3003074c)

<br>

## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
