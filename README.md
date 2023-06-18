# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file.

## ALGORITHM:

### Step 1:
Import pandas module as pd.

### Step 2:
Using pd.read_csv() method read the CSV file.

### Step 3:
Using df.head() print the first 10 rows of the CSV file.

### Step 4:
Using df.tail() print the last 5 of the CSV file.

### Step 5:
Using len(df.axes[]) print the toal no.of rows and columns with argument 0 for row and argument 1 for column.

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
![image](https://github.com/SivaramakrishnanBaskar/Read-from-CSV/assets/119476322/9eb458c9-0054-4404-ad13-56fb9dffd265)

## RESULT:
Therefore the above code is successfully executed to read a csv file using pandas.
