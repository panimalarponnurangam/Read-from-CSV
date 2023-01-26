# Read-from-CSV

## AIM:
To write a python program for getting the read from csv a text

## ALGORITHM:
### Step 1:
start the python
### Step 2:
import pandas
### Step 3:
mention the csv file which is to be read
### Step 4:
read the contects of the csv file using df.read function
### Step 5:
end the program

## PROGRAM:
~~~
Developed by: panimalar.p
RegisterNumber:  22009107

import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('col:',len(f.axes[1]))
~~~
## OUTPUT:
![Screenshot (219)](https://user-images.githubusercontent.com/121490826/214850601-9ae72fee-718e-42d4-9da6-99cf67e6658d.png)


## RESULT:
A python program to read data from csv files has been created successfully
