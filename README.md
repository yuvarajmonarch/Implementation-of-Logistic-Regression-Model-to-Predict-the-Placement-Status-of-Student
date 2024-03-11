# Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student

## AIM:
To write a program to implement the the Logistic Regression Model to Predict the Placement Status of Student.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm

1.Use the standard libraries in python for finding linear regression.

2.Set variables for assigning dataset values.

3.Import linear regression from sklearn.

4.Predict the values of array.

5.Calculate the accuracy, confusion and classification report by importing the required modules from sklearn.

6.Obtain the graph.

## Program:
```
/*

import pandas as pd
data=pd.read_csv("/content/Placement_Data.csv")
data.head()

data1=data.copy()
data1=data1.drop(["sl_no","salary"],axis=1)
data1.head()

data1.isnull()

data1.duplicated().sum()

from sklearn.preprocessing import LabelEncoder
le=LabelEncoder()
data1["gender"]=le.fit_transform(data1["gender"])
data1["ssc_b"]=le.fit_transform(data1["ssc_b"])
data1["hsc_b"]=le.fit_transform(data1["hsc_b"])
data1["hsc_s"]=le.fit_transform(data1["hsc_s"])
data1["degree_t"]=le.fit_transform(data1["degree_t"])
data1["workex"]=le.fit_transform(data1["workex"])
data1["specialisation"]=le.fit_transform(data1["specialisation"])
data1["status"]=le.fit_transform(data1["status"])
data1

x=data1.iloc[:,:-1]
x

y=data1["status"]
y

from sklearn.model_selection import train_test_split
x_train,x_test,y_train,y_test=train_test_split(x,y,test_size=0.2,random_state=0)

from sklearn.linear_model import LogisticRegression
lr=LogisticRegression(solver="liblinear")
lr.fit(x_train,y_train)
y_pred=lr.predict(x_test)
y_pred

from sklearn.metrics import accuracy_score
accuracy=accuracy_score(y_test,y_pred)
accuracy

from sklearn.metrics import classification_report
classification_report1=classification_report(y_test,y_pred)
print(classification_report1)

lr.predict([[1,80,1,90,1,1,90,1,0,85,1,85]])


Program to implement the the Logistic Regression Model to Predict the Placement Status of Student.
Developed by: Yuvaraj B
RegisterNumber: 21222240186 
*/
```

## Output:
![the Logistic Regression Model to Predict the Placement Status of Student](sam.png)
![Screenshot 2024-03-11 143621](https://github.com/yuvarajmonarch/Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student/assets/122221735/bb59de65-257f-4500-94c3-a595e2fd47ca)
![Screenshot 2024-03-11 143606](https://github.com/yuvarajmonarch/Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student/assets/122221735/983a2a6b-c135-47f9-aaad-266957f90d64)
![Screenshot 2024-03-11 143553](https://github.com/yuvarajmonarch/Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student/assets/122221735/543cbbc7-1dad-436b-85ad-25b5d3bd00c4)
![Screenshot 2024-03-11 143651](https://github.com/yuvarajmonarch/Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student/assets/122221735/23245502-1c48-4314-8fc5-c8dd4a88712a)
![Screenshot 2024-03-11 143642](https://github.com/yuvarajmonarch/Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student/assets/122221735/0c0c96d0-3763-48fb-b388-e2650ebd901f)
![Screenshot 2024-03-11 143633](https://github.com/yuvarajmonarch/Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student/assets/122221735/dcf18bb2-74e4-4d4d-8bc2-15c14c046a30)
![Screenshot 2024-03-11 143703](https://github.com/yuvarajmonarch/Implementation-of-Logistic-Regression-Model-to-Predict-the-Placement-Status-of-Student/assets/122221735/0e8c886f-5294-43cd-a5ce-5ea1658a1ce2)




## Result:
Thus the program to implement the the Logistic Regression Model to Predict the Placement Status of Student is written and verified using python programming.
