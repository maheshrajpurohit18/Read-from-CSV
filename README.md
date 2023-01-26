# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:

Start the python.

### Step 2:

Import pandas.

### Step 3:

Mention the CSV file which is to be read.

### Step 4:

Read the contents of the CSV file using df.read function.

### Step 5:

End the program.

## PROGRAM:
```
Developed by: mahesh raj purohit
registration no: 22008605

import pandas as pd
df = pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column", len(df.axes[0]))
print("rows", len(df.axes[1])
```

## OUTPUT:
![Screenshot from 2023-01-26 11-50-20](https://user-images.githubusercontent.com/118749665/214771979-96435c31-1fb2-4920-bc09-2d8c4f0158a4.png)


## RESULT:
A python program to read data from CSV files has been created successfully.
