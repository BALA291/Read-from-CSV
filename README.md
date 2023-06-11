# Read-from-CSV

## AIM:
To write a python program for reading content from a CSV file
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
Print the output
## PROGRAM:
```
DEVELOPED BY: BALAMURUGAN B
REG NO:212222230016
import pandas as pd
f=pd.read_csv('/content/nba.csv')
print(f.head(10))
print(f.tail())
print('Number of Row:', len(f.axes[0]))
print('Number of column:',len(f.axes[1]))
```
## OUTPUT:
![py6prog](https://github.com/BALA291/Read-from-CSV/assets/120717501/83cec347-6a15-4e39-a2bd-3324cc8d5439)

![py6output](https://github.com/BALA291/Read-from-CSV/assets/120717501/38b065b2-be6d-46e7-abe7-df0cf0765a6a)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
