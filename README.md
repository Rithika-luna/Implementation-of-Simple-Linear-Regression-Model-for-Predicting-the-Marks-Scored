# Implementation-of-Simple-Linear-Regression-Model-for-Predicting-the-Marks-Scored

## AIM:
To write a program to predict the marks scored by a student using the simple linear regression model.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. TYPE THE PROGRAM IN JUPITER
2. ATTACH THE CSV FILE
3. RUN THE CODE
4. MAKE A SCREENSHOT

## Program:
```
/*
Program to implement the simple linear regression model for predicting the marks scored.
import numpy as np 
import matplotlib .pyplot as plt
import pandas as pd
from sklearn.metrics import mean_absolute_error, mean_squared_error,r2_score
df =pd.read_csv("student_scores.csv")
df.head(10)
plt.scatter(df['Hours'],df['Scores'])
plt.xlabel('Hours')
plt.ylabel('Scores')
x = df.iloc[:,0:1]
y = df.iloc[:,-1]
y
from sklearn.model_selection import train_test_split
X_train,X_test,Y_train,Y_test = train_test_split(x,y,test_size =0.2,random_state = 0)
from sklearn.linear_model import LinearRegression
lr = LinearRegression()
lr.fit(X_train,Y_train)
X_train
Y_train
Y_pred=lr.predict(X_test)
plt.scatter(df['Hours'],df['Scores'])
plt.xlabel('Hours')
plt.ylabel('Scores')
plt.plot(X_train,lr.predict(X_train),color = 'red')
lr.coef_
lr.intercept_
mse = mean_squared_error(Y_test,Y_pred)
rmse = np.sqrt(mse)
mae = mean_absolute_error(Y_test,Y_pred)
r2 = r2_score(Y_test,Y_pred)
print("MSE:",mse)
print("RMSE",rmse)
print("MAE",mae)
print("R2",r2)


Developed by: S RITHIKA
RegisterNumber:  212225040344
*/
```

## Output:
<img width="849" height="659" alt="image" src="https://github.com/user-attachments/assets/8829b461-bc99-44a6-9cca-4ebfc2ec4f00" />



## Result:
Thus the program to implement the simple linear regression model for predicting the marks scored is written and verified using python programming.
