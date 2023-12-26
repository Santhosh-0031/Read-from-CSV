# Read-from-CSV

## AIM:
write a python program to read a csv file

## ALGORITHM:
### Step 1:
Import pandas modules as pd

### Step 2:
Read a csv file name cars.csv

### Step 3:
Print the first five rows and last five rows

### Step 4:
Print the lenght of the rows and columns

### Step 5:
End the program

## PROGRAM:
```
"""
write a program to read a csv file
Developed by : SANTHOSH KUMAR R
Reference no: 23013562
"""
import pandas as pd
df=pd.read_csv("cars.csv")
print(df.head())
print(df.tail())
print("Rows",len(df.axes[0]))
print("Columns",len(df.axes[1]))
```

## OUTPUT:
![Screenshot 2023-12-26 165903](https://github.com/Santhosh-0031/Read-from-CSV/assets/145551108/ff82908e-1fe3-48b7-8d1e-0414ac58914e)

## RESULT:
Thus the program is written to read a csv file.

