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
![output](/Screenshot%202023-07-25%20081716.jpg)
![output](/Screenshot%202023-07-25%20082600.jpg)
i) CSV FILE 
![output](/Screenshot%202023-07-25%20082240.jpg)

## RESULT:
Thus the program is written to read a csv file.

