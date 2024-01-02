# Read-from-CSV

## AIM:
To read from CSV

## ALGORITHM:
### Step 1:
Import pandas as pd.

### Step 2:
Read the CSV file using read_csv method.

### Step 3:
Use head and tail method to get the required contents from the file.

### Step 4:
Use len() method to get the number of rows and columns

### Step 5:
Print the output:

## PROGRAM:
```
# Program to read a file from csv
# Developed by:Kishore A
# Register number:212223110022
import pandas as pd
f=pd.read_csv("nba.csv")
print(f.head(10))
print(f.tail())
print('Row:',len(f.axes[0]))
print('Col:',len(f.axes[1]))
```
## OUTPUT:
![Screenshot 2024-01-01 134854](https://github.com/Ashwathm12/Read-from-CSV/assets/138849225/cff2cb83-1c4f-4609-baba-95234bd5263d)


## RESULT:
Thus a python program to read the contents of a CSV file has been executed successfully.
