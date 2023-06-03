# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Load the CSV into a DataFrame
### Step 2:
Print the number of contents to be displayed using df.head().
### Step 3:
The number of row returned is defined in pandas option settings.
### Step 4:
Check your systems maximun column with the pd.options.display.max_columun statement.
### Step 5:
Increase the maximum number of rows to display the entire DataFrame.
## PROGRAM:
```
### Developed By:Sivaramakrishnan B
### Register Number::212222110044
import pandas as pd
df= pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("column",len(df.axes[0]))
print("rows",len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/SivaramakrishnanBaskar/Read-from-CSV/assets/119476322/fc318083-8776-4372-9f09-2c05000c1a3e)

## RESULT:
Therefore the above code is successfully executed to read a csv file using pandas.
