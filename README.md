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
![kk](https://user-images.githubusercontent.com/118749665/214772089-cde595e3-8ae3-4b40-b298-443e9a39d8fa.png)



## RESULT:
A python program to read data from CSV files has been created successfully.
