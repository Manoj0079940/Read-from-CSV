# Read-from-CSV

## AIM:
To write a python program for reading content from a csv file

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame.
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of rows returned is defined in Pandas option settings.
### Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.

## PROGRAM:
```
Read-from-CSV
AIM:
To write a python program for reading content from a csv file

import pandas as pd
df = pd.read_csv('salary.csv')
print(df.head(10))
print(df.tail())
print("Number of rows:",len(df.axes[0]))
print("Number of columns:",len(df.axes[1]))

```

## OUTPUT:
![alt text](image.png)

## RESULT:
Thus python program for reading content from a CSV file is successful.
