# Read-from-CSV

## AIM: 
To write a program to read a csv file.
## ALGORITHM:
### Step 1:
Import pands module as pd.
### Step 2:
Read a csv file name cars.csv.
### Step 3:
Print the first five rows and last five rows.
### Step 4:
Print the length of the rows and columns.
### Step 5:
End the program.
## PROGRAM:
```
# Program to read a csv file.
# Developed by:STANLEY S
# Reference number: 23014354
import pandas as pd
df = pd.read_csv("cars.csv")
print(df.head())
print(df.tail())
print("Rows", len(df.axes[0]))
print("Columns", len(df.axes[1]))
```
## OUTPUT:
![image](https://github.com/STANLEY-13/Read-from-CSV/assets/148198816/bafdd7e1-62fc-477b-96f8-1dc72679c291)
![WhatsApp Image 2024-01-02 at 1 39 55 PM](https://github.com/STANLEY-13/Read-from-CSV/assets/148198816/efa99053-0a7f-4988-b0fa-3cfdecba99f6)
## csv File:
![WhatsApp Image 2024-01-02 at 1 41 04 PM](https://github.com/STANLEY-13/Read-from-CSV/assets/148198816/ec8f0434-0eeb-4103-b513-12b1d3e98d5e)


## RESULT:
Thus the program is written to read a csv file
