# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:
### Step 1:
Import pandas as pd.
### Step 2:
Read the CSV file using read_csv method.
### Step 3:
Use head and tail method to get the required contents from the file.
### Step 4:
Use len() method to get the number of rows and columns.
### Step 5:
Print the output.

## PROGRAM:
```
### Developed By:Sivaramakrishnan B
### Register Number::212222110044
import pandas as pd
df=pd.read_csv("nba.csv")
print(df.head(10))
print(df.tail())
print("Column",len(df.axes[0]))
print("Rows",len(df.axes[1]))
```

## OUTPUT:
![image](https://github.com/SivaramakrishnanBaskar/Read-from-CSV/assets/119476322/9b051e29-ff8f-468d-8397-eedd93504e38)

## RESULT:
Therefore the above code is successfully executed to read a csv file using pandas.
