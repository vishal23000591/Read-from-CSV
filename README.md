# Read-from-CSV

## AIM:
To write a python program to read a csv file and print its details as output.
## EQUIMENTS REQUIRED:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Moodle-Code Runner
## ALGORITHM:
### Step 1:
Start the program and import pandas
### Step 2:
Open the csv file cars(1).csv
### Step 3:
Next use df.head() to print the columns from the top.
### Step 4:
Next use df.tail() to print the columns from the bottom.
### Step 5:
Finally, use df.loc() the print the required details from the file.
## PROGRAM:
```
#Program to read a csv file.
#Developed by: Vishal S
#Register Number: 212223110063

import pandas as pd
df=pd.read_csv('cars (1).csv')
print(df.head(3))
print(df.tail(7))
print(df.axes[0],len(df.axes[0]))
print(df.axes[1],len(df.axes[1]))
print(df.loc[2:6,:])
```
## OUTPUT:
![Output](</Readcsv output.png>)
## RESULT:
Thus the csv file is read successfully and required details are given as output using the python program.