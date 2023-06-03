# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.
## ALGORITHM:
### Step 1:
start python.
### Step 2:
import pandas.
### Step 3:
the number of rows returned is defined in pandas option settins
### Step 4:
read the contents of the CSV file using the df.read function.
### Step 5:
increase the maximum number of rows to display the entire dataframe.
## PROGRAM:
```
### NAME:Sivaramakrishnan B
### REGISTER NUMBER:212222110044
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
