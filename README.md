# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
start program

### Step2
import pandas

### Step3
create a dataframe and further process

### Step4
end program


## Program:
```
Developed by: VARNIKA.P
Register No: 23008344


import pandas as pd
from sklearn import linear_model

df = pd.read_csv("cars (1).csv")
X=df[['Weight','Volume']]
Y=df['CO2]
regr=linear_model.LinearRegression()
regr.fit(X,Y)
print('Coefficient:',regr.coef_)
print('Intercept:',regr.intercept_)
predictedCO2=regr.predict([[3300,1300]])
print('Predicted CO2 for the corresponding weight and volume',predictedCO2)




```
## Output:

![image](https://github.com/23008344/Multivariate-Linear-Regression/assets/145742655/966f32fa-7463-4a88-9e1a-dc436a9e0150)



## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
